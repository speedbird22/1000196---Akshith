<h1 align="center">Hi 👋, I'm Akshith Reddy</h1>
<h3 align="center">A passionate Programmer from India</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=speedbird22&label=Profile%20views&color=0e75b6&style=flat" alt="speedbird22" /> </p>

- 🌱 I’m currently learning **Java, Python**

- 💬 Ask me about **HTML, CSS, C++**

- 📫 How to reach me **akshithreddyworld2020@gmail.com**

- ⚡ Fun fact **HTML is my most favorite language**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=speedbird22&show_icons=true&locale=en&layout=compact" alt="speedbird22" /></p>


<H1> ABOUT MY PROJECT - Olympix Insights</H1>

<h4>Olympix Insights is a data-driven analytical application designed to explore the historical and contemporary trends in the Olympic Games. Leveraging datasets like athlete events, country region mappings, and detailed medal statistics, this app offers a deep dive into various facets of the Olympics, including athlete demographics, country performances, and gender participation. Users can visualize patterns, identify trends, and gain insights into Olympic data through a series of dynamic and visually appealing graphs.

Key Features and Graph Descriptions:

Top 10 Countries with Most Gold Medals

Purpose: Displays the top-performing countries in terms of gold medals won across all Olympic events.
Graph Type: Horizontal bar graph.
Insight: Highlights the dominance of certain countries over others in securing gold medals.
Top 10 Countries in Gymnastics Over the Years

Purpose: Identifies the top countries excelling in Gymnastics, showcasing their consistency and prowess in the sport.
Graph Type: Horizontal bar graph.
Insight: Reflects trends in specific sports and which countries have historically excelled in Gymnastics.
Gender Participation Over Time

Purpose: Analyzes the participation of male and female athletes across all years of the Olympics.
Graph Type: Stacked bar chart.
Insight: Reveals the progress of gender inclusion in sports over decades.
Sports Count Over Time

Purpose: Tracks the number of unique sports represented in the Olympics over time.
Graph Type: Line plot.
Insight: Displays how the diversity of sports has expanded or fluctuated historically.
Age Distribution of Gold Medalists

Purpose: Studies the age range of athletes who win gold medals.
Graph Type: Histogram with KDE overlay.
Insight: Highlights the age brackets where athletes peak in performance.
Summer Sports Over Time

Purpose: Focuses on the evolution of summer sports across Olympic history.
Graph Type: Line plot.
Insight: Displays trends specific to summer sports and their increasing diversity.
Winter Sports Over Time

Purpose: Mirrors the analysis for winter sports, focusing on their growth and diversity over the years.
Graph Type: Line plot.
Insight: Highlights the evolution of winter sports' popularity.
Average Height of Male and Female Athletes Over Time

Purpose: Tracks changes in average height for male and female athletes.
Graph Type: Line plot.
Insight: Examines physiological trends among athletes over time.
Top Performing Athletes in Ice Hockey

Purpose: Identifies top athletes in Ice Hockey by their medal count, segmented by gender.
Graph Type: Horizontal bar graph with gender-wise distinction.
Insight: Highlights exceptional individual performers in a team-centric sport.
India's Performance in All Olympic Games

Purpose: Evaluates India's medal achievements across all Olympic events.
Graph Type: Bar chart.
Insight: Sheds light on India’s strengths and areas for improvement in international sports.
Analysis of Outcomes:
Top Countries in Gold Medals:

Outcome: The graph highlights dominant countries such as the USA, USSR (former), and China. It reflects the influence of economic and infrastructural investment in sports.
Insight: Encourages understanding of sports hegemony and disparities in resource allocation.
Gymnastics Over the Years:

Outcome: Gymnastics sees continued dominance by countries like the USA, Russia, and China.
Insight: Gymnastics relies heavily on discipline and long-term athlete programs.
Gender Participation:

Outcome: There’s a significant rise in female participation over time, closing the gender gap.
Insight: Reflects global advancements in gender equity in sports.
Sports Count Over Time:

Outcome: Both summer and winter sports show growth, with summer sports exhibiting a steeper increase.
Insight: Indicates the growing inclusivity of diverse sporting disciplines.
Age Distribution:

Outcome: Most gold medalists are in their late teens to early thirties.
Insight: Highlights the prime age for peak athletic performance.
Average Height:

Outcome: Gradual increases in height, especially for male athletes, were observed.
Insight: Reflects physiological evolution and athlete specialization in certain sports.
India’s Performance:

Outcome: A stronger medal count in recent years, but overall performance still lags behind global leaders.
Insight: Suggests a need for better infrastructure and grassroots programs.
Errors Faced During the Process:
Missing and Null Values:

Many rows in the dataset had missing age, height, or medal data.
Solution: Dropped rows with null values in critical fields.
KeyError for 'year':

The 'year' column was occasionally read incorrectly due to formatting.
Solution: Ensured 'year' was numeric by using pd.to_numeric.
Palette Errors in Seaborn:

Some color palettes were invalid (e.g., "gold").
Solution: Switched to valid palettes like YlOrBr, viridis, or coolwarm.
Inconsistent Column Names:

Column names differed across datasets.
Solution: Standardized column names to lowercase and stripped spaces.
Mismatch in NOC Codes:

Some NOC codes in the athlete events dataset did not match the NOC regions dataset.
Solution: Used a left join to avoid data loss but noted discrepancies.
Data Overlap in Seasons:

Misclassification of summer and winter sports in some cases.
Solution: Filtered explicitly by the 'season' column.
Visualization Overlaps:

Overlapping legends and labels in some graphs.
Solution: Used tight_layout() to adjust spacing.
</h4>
