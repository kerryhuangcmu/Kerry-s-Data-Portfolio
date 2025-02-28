| [home page](https://kerryhuangcmu.github.io/Kerry-s-Data-Portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

## Visualizing Government Debt
This is based on a homework discussion for my course, Telling Stories with Data. 
I visited the OECD's data site at https://www.oecd.org/en/data.html and downloaded the dataset. 
I then created the following data visulization:
<div
  class="tableauPlaceholder"
  id="viz1740780666044"
  style="position: relative"
>
  <noscript
    ><a href=" "
      ><img
        alt="Government Debt  Highlight Table (1995-2019) "
        src="https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingGovernmentDebt_17378726861170&#47;GovernmentDebtHighlightTable1995-2019&#47;1_rss.png"
        style="border: none" /></a ></noscript
  ><object class="tableauViz" style="display: none">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param
      name="name"
      value="VisualizingGovernmentDebt_17378726861170&#47;GovernmentDebtHighlightTable1995-2019"
    />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
    <param
      name="static_image"
      value="https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingGovernmentDebt_17378726861170&#47;GovernmentDebtHighlightTable1995-2019&#47;1.png"
    />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById("viz1740780666044");
  var vizElement = divElement.getElementsByTagName("object")[0];
  vizElement.style.width = "100%";
  vizElement.style.height = divElement.offsetWidth * 0.75 + "px";
  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


Part 2’s graph shows all the participating countries' debt to GDP ratios, through 1995-2019. When trying to change to another data visualization, the graphs all became messy due to the massive number of countries. Therefore, in part 3, I decided to use a subset of data and only focused on the top five countries with the highest governmental debts in 2022: Japan, Greece, Italy, USA, and France. Although 2022 is not in the dataset provided in part 2, it is useful because I was able to see the trend of how these five countries performed from 1995-2019 (as part 2 dataset given), prior to these countries' performance in 2022. Since Japan did not provided the data in 2019, I took out 2019 from the variable "time". 

# My change to the visualization

<div
  class="tableauPlaceholder"
  id="viz1740780915406"
  style="position: relative"
>
  <noscript
    ><a href=" "
      ><img
        alt="Government Debt of 5 countries from 1995-2018 "
        src="https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingGovernmentDebt_Part3&#47;Sheet2&#47;1_rss.png"
        style="border: none" /></a ></noscript
  ><object class="tableauViz" style="display: none">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="VisualizingGovernmentDebt_Part3&#47;Sheet2" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
    <param
      name="static_image"
      value="https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;VisualizingGovernmentDebt_Part3&#47;Sheet2&#47;1.png"
    />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
    <param name="filter" value="publish=yes" />
  </object>
</div>
<script type="text/javascript">
  var divElement = document.getElementById("viz1740780915406");
  var vizElement = divElement.getElementsByTagName("object")[0];
  vizElement.style.width = "100%";
  vizElement.style.height = divElement.offsetWidth * 0.75 + "px";
  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

I chose the area chart because the bulk of each shaded area clearly represents how much % of GDP there is for each country: The bigger the area, the higher the % of GDP. With this area chart, we are able to see an overall increasing trend in each of the five countries’ debt. We are also able to compare and contrast between these five countries. For example, Japan’s debt continued to rise starting in 2007 and continued to be at the top due to having the highest debt. We could also see how Greece and France fluctuated the most, and both experienced a sharp increase in 2011. 

The area chart is a more effective representation than a heatmap because viewers can have a more immediate general understanding of the trend of debts of the five countries. However, the tradeoff might be that we don’t know the exact numbers of %. Although the heatmap is more detailed, the amount of data can make it hard for viewers to get an intuitive understanding. In one of the previous readings it mentioned we only see a few things at once (39), so having too much data/information might create the opposite effect of reaching clarity. The heatmap requires the viewer to read each number carefully. One must finish reading each country's yearly number to gain a general understanding of its % trend, which is not as effective as an area map. That being said, the area map should only be used when there are less countries. Otherwise, it can become too crowded. 

# Reference
https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2022

Good Charts Chapter 2, pg. 39

