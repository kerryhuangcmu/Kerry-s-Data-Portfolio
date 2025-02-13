| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and Redesign: Improve Data Visualization and Analysis on Universities' Student Loans in the United States

## Step one: the visualization

In my Telling Stories with Data course with Professor Goranson, we worked on redesigning a data visualization from either a professional organization or government agency. Here is the example I picked:
MakeoverMonday: 12/06/2021, What Schools Create the Most Student Loans in the U.S.? 
https://howmuch.net/articles/university-with-the-most-student-loan-originations-in-every-state  

![alt text](https://github.com/kerryhuangcmu/Kerry-s-Data-Portfolio/blob/222471322aad97e3461282a0cbfd91181c1f8eb4/MakeoverMonday.png?raw=true)

Student loans/debt is a pressing issue, because although receiving education seems to be a right, in some particular places, the cost of tuition can be a significant financial burden for people. This graph illustrates the universities that rank highest in student loans in each state, highlighting how this issue is represented throughout the country. 

I selected this particular data visualization because while it has the potential to tell a compelling story and raise awareness on an important problem, the execution of the graph is unsuccessful in doing so. Rather, the graph presents too much information without clear organization, making it difficult for the viewers to gain meaningful insights clearly, quickly, and effectively. When I first clicked on the link, I was overwhelmed by the colors and the massive amount of information crammed all into the map. Although contextual explanations in the article helped me understand what the visualization is about, it contained too much information and took a while to process. There was a need to redesign it. The graph is trying to talk about too many things, making it lose focus. My goal is to redesign this visualization using some parts of the data that I found the most important in telling a clearer, stronger story about student loans in the United States. 

## Step two: the critique

Overall, although the data visualization contains a lot of useful information, it is not very effective. The idea of map is good, but having it static crams all information and makes it crowded. It is better to make it interactive, but to make the visualization straight to the point, it will be better to reduce the amount of information. 

Using Stephen Few’s Data Visualization Effectiveness Profile (https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf ) I critiqued the data visualization based on Few’s 7 criterias and assigned a score from 1-10 for each criteria, with 1 being the least ideal : 

Usefulness - 7
- Articulates a topic that matters. Information is overall useful (ex. name of schools, type of schools, and loan amounts) but is trying to discuss too much in a single graph, which makes it ineffective.  

Completeness - 6
- The graph includes more information than necessary, making it harder to digest. A more focused approach would improve clarity.
  - For example, in “Total Loans Originated”, there are 12 variables matching type of school (public, private, and proprietary) with 4 categories (Less than $100M, $100M-$299M, $300M-$499M, and $500M and More) and 9 colors.

Perceptibility - 5
- Hard to perceive with minimal effort. Requires actually observing the graph for a while. The graph is not effective in the way it presents its information.

Truthfulness - 10
- Accurate and valid data, tackles a real issue, represents what it claims.

Intuitiveness - 5
- Similarly to perceptibility, the graph is not intuitive to be easily understood. 
- The graph forces viewers to make multiple connections. Colors represent both the type of school and the loan amounts, making the interpretation less immediate. 

Aesthetics - 5
- Too many colors that are highly saturated, not pleasing to the eye.
- School logos are different sizes and some are unclearly displaced, they also add excessive graphic elements that clutters the map design.
- A lot of protruding lines and logos on the right side of the graph makes it look busy, and the visual weight of the graph is not evenly distributed. 

Engagement - 8
- The topic itself is an engaging topic, but the visualization can be distracting. It really depends on how much patience one has reading this graph. 

How to implement the redesign:

I will use a bar chart instead of a map, as geographic representation can sometimes be more difficult to locate states quickly. Maps have spatial limitations, especially for smaller states, making it harder to display information. Instead, I will list the state in parentheses next to each university’s name. Since I intend my target audience to be upcoming college students, I want to focus the attention on how high student loans can play into the judgement of selecting education. Therefore, to keep the graph focused and avoid overcrowding, I will use only the “Top 10 Universities With the Highest Loan Originations by State” rather than all 50 states’ data. I will also simplify the color scheme by using distinct colors for school types (public, private-nonprofit, proprietary). The current approach—using 12 colors to represent both school type and loan amounts—is overly complex and confusing and requires more than one graph if implemented. 

Evaluation of the critique tool:

For this data visualization redesign critique, Stephen Few’s Data Visualization Effectiveness Profile is highly effective. It provides a clear, structured framework, which allows designers to think from different angles. Another method of critique is the Good Charts Method by Scott Berinato, which contains 5 steps that are more general instructions such as making notes on observations and what one dislikes or likes. As we can compare, Few’s approach offers specific criterias that provides structured directions for the designer to execute, each with clear explanations and measurable scales, whereas the Good Charts Method relies on more subjective questions that require more interpretation and judgment from the designer. As a designer newbie, I think using Few’s method to test the functionality of a data visualization creates more precise and actionable outcomes.
One thing that Few’s method can improve on is to add a measure of “Coloring Effectiveness” to Few’s method. While color overlaps a little with the criterias of aesthetics and readability, it also plays a crucial role in conveying meaning. This category could include “consistency” (ensuring the color scheme aligns with the dataset’s message) and “attention-focusing” (assessing whether color guides or distracts viewers).


## Step three: Sketch a solution
![alt text](https://github.com/kerryhuangcmu/Kerry-s-Data-Portfolio/blob/main/Step%203.png?raw=true)
Source: draw.io

## Step four: Test the solution

This is the script I used during the critique in class. I modified the questions from a sample provided by Professor Goranson.
- What do you think this data visualization is about?
- Is it clear what this data visualization is telling you?
- What do you think about the colors in this visualization?
- Who do you think the intended audience for this visualization is?
- Is there anything you would change or do differently? 


Results: 

|  Question |  Interview 1 (MEIM interviewee)| Interview 2 (MAM interviewee) |
|---|---|---|
| What do you think this data visualization is about?  |  10 universities with highest loans |  10 universities with highest loans |
| Is it clear what this data visualization is telling you?  | yes | yes|
| What do you think about the colors in this visualization?  |Good separation of variables using colors| They look fine, not distracting or too sharp  |
|Who do you think the intended audience for this visualization is? | Unclear since the title doesn't really stress whether it is school or student loans  | Unclear |
| Is there anything you would change or do differently?   | Think about who I’m targeting with this info, so it can better help me narrow down which target audience I’m trying to tell this story to. Rmove the lines in the background of the graph and add numbers on top of the bar.   | Unsure about what the public, private, and proprietary icons indicate. It was confusing whether those mean the type of schools or the type of loans. Can be confused with the type of loans,  make it clear what variables are being discussed.|

Synthesis: 

My graph was overall clear, both understood what the topic is about, and both gave me valuable feedback on how I can improve my graph. The MEIM student suggested that I think about who I’m targeting with this info, so it can better help me narrow down which target audience I’m trying to tell this story to. She also suggested that I can remove the lines in the background of the graph and add numbers on top of the bar. Having precise numbers of the loans will achieve a better understanding of the audience. When looking at my graph, the MAM student was unsure about what my public, private, and proprietary icons indicate. It was confusing whether those mean the type of schools or the type of loans. She originally thought those were categories for the type of loans, so she suggested that I make it clear what I’m talking about.

One key pattern that emerged from the feedback was that both of my critics felt that I needed to justify my data choices more clearly. Although the original dataset contains numbers for all 50 states’ highest student loans, I narrowed it down to only 10 schools, which requires a better explanation of why I made this choice, other than stating there is too much data. I learned from the critique feedback that as a designer, I have preconceived knowledge that others may not. So when I make decisions about the dataset, I need to keep in mind that there is an information gap between the designer and the viewers, and how the designer chooses to present the data visualization influences what viewers understand. This is why it is important to have a clear goal of what specific story I want to tell. This ensures that my data visualization is effective. 

The design changes I will implement will be as follows:
- Take out the line in the background of the graph
- Add numbers to the top of each bar
- Put a note indicating that “public, private, proprietary” means types of student loans
- Make it clear in the title that it is student loan
- Refine what type of story I want to tell and reorganize and pick the data accordingly


## Step five: build the solution

I first redesign the bar chart according to the critique in class.

![alt text](https://github.com/kerryhuangcmu/Kerry-s-Data-Portfolio/blob/ac156a15adfbf6718b3baf872662f8444325a862/Redesign-Bar%20chart.png?raw=true)

Here is the public Tableau link to it: https://public.tableau.com/app/profile/kerry.huang8806/viz/Top10Universitieswiththehigheststudentloansinthestates2020-2021/Sheet1?publish=yes 

After the critique in class, I realized that my story needed stronger reasoning. I began to rethink how I should design the data visualization. Initially, I wanted to add a bar graph on Top 10 Universities with the Least Loan Originations by State. I planned to compare and contrast the top 10 with the highest and top 10 with the lowest loans. My goal was to inform prospective college students to use this data to assess potential financial risks. However, after further research, I found that loan amounts don’t necessarily correlate with a school’s performance. For example, New York University has 405 million loans, while Pacific Islands University has 1 million loans in total, but that does not mean that Pacific Islands University is necessarily the better option, or vice versa. To make logical correlations, it is important to use more data sources.

I found an interactive map online from The Institute for College Access & Success, which has a report that documents student debt of 50 states from the class of 2020. The data contains the average debt of graduates from 2020, along with other information such as percent of graduates at schools, fall enrollment rates, and other variables. I selected the average debt of graduates from each state as the source of new data, which reduces the data in the original interactive map. Then in Tableau, I inserted the data and used two color schemes: the more blue it is, the less debt on average the student has in the state. The more orange, the more debt on average the student has. This also refined the color schemes the original data since the new colors are more intuitive in their meanings (ex. blue is less threatening, which indicates lower loans).

![alt text](https://github.com/kerryhuangcmu/Kerry-s-Data-Portfolio/blob/08abffc6c854c011e3e0f738732ce458f1205686/Redesign-Interactive%20Map.png?raw=true) 

I advise using the public Tableau link to the refined interactive map so you can hover around for the specific data on each states' avaerage student loans:
https://public.tableau.com/app/profile/kerry.huang8806/viz/AverageStudentDebtbyState2020/Sheet1?publish=yes

The target audience for these two visualizations are policy makers and government officials in the realm of education. These are used to help them understand the varying levels of debt in different states. Using the redesigned interactive map, we can see that on average in the east coast, student graduates have more debt as compared to the west. This could represent that universities in the west are generally more affordable than the east, or people are richer in the west. Therefore, with regards to funding policies, the government could perhaps increase the educational subsidies in the east to improve the equity of access to education across the country. Connecting with the bar chart, we can gather more specific information on the same issue of student loans across states. The bar graph showing the top 10 universities with the highest student loans during 2020-2021 can help the government identify the institutions where the most loans originated from. Using this information, the government can investigate the reasons behind the large amount of debts. The government can also determine whether it makes sense for these colleges to have these huge amounts of debts. 

With the interactive map, we can understand the debt coming from the universities in the context of the average debt of the states. For example, California generally has a low debt, as the blue indicates, we would imagine USC having less student loans, but the bar chart shows that USC ranked the 7th highest in student loans. Government can use this information to investigate the problem and to see whether more funding is needed to support students in schools with higher debt. 

Overall, these two graphs can provide some guidance for governmental officials to have a focused way to look into the issue of student loans/debt across the country. 


## References
- MakeoverMonday (https://makeovermonday.co.uk/)
  - 12/06/2021, What Schools Create the Most Student Loans in the U.S.? 
  - https://howmuch.net/articles/university-with-the-most-student-loan-originations-in-every-state  
- Stephen Few's Data Visualization Effectiveness Profile: 
  - https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf
-  Student Debt and the Class of 2020 Interactive Map:
   - https://ticas.org/interactive-map/

## AI acknowledgements
I used AI to structure my explanations in Step 2: the critique section. I wrote the critique first and asked ChatGPT to make my critique more concise and grammatically correct.

