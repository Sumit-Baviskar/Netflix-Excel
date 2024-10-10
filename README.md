# :chart_with_upwards_trend: Netflix Data Analysis (Excel Project) :chart_with_upwards_trend:

Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally.
So as a data analyst, we are given task to analyze the given data and answer the business question  given by the manager .



# :green_book: **Introduction :**


The rapid growth of digital streaming platforms has transformed the entertainment landscape, with Netflix at the forefront of this revolution. Over the past decade, Netflix has expanded its content library to include a wide variety of movies, TV shows, documentaries, and more, catering to a global audience. As one of the leading on-demand streaming services, Netflix's strategy revolves around continuously expanding and diversifying its content to retain existing subscribers and attract new ones.

This project focuses on analyzing Netflix’s content data, with a particular emphasis on understanding trends in its content production and distribution. Through an interactive dashboard, various business questions related to the distribution of movies and TV shows, key actors, top directors, genre trends, and content production across countries are addressed. The analysis seeks to provide valuable insights into how Netflix is growing its library, which content categories are performing well, and which geographic regions and genres the platform is emphasizing.

The dataset used includes detailed information on the show ID, title, type (movie or TV show), director, cast, country of production, release year, and genre, among other attributes. By leveraging this data, the project offers an in-depth exploration of Netflix’s content strategy and provides recommendations on where the platform should focus its future efforts to enhance its global appeal and sustain its leadership in the streaming industry.


# :green_book: **Purpose of the Project :**

The purpose of this project is to **analyze Netflix’s content library** and provide **data-driven insights** that can help inform strategic business decisions. By examining key metrics related to the distribution of movies, TV shows, genres, actors, directors, and countries of production, this analysis seeks to:

  1. **Understand Trends in Content Distribution** – Investigate how Netflix allocates resources between movies and TV shows and whether there are any patterns or shifts in recent years.
   
  2. **Identify Key Contributors** – Analyze which directors and actors have the largest presence on the platform, and explore how they contribute to Netflix’s content strategy.
   
  3. **Explore Genre Popularity** – Examine the types of content (e.g., dramas, documentaries, comedies) that dominate Netflix's library to identify which genres resonate most with audiences.
   
  4. **Assess Geographical Content Diversity** – Identify the countries that are producing the most content on Netflix and assess whether Netflix is adequately addressing global content needs.

  5. **Provide Strategic Recommendations** – Based on the insights gained from the analysis, provide actionable recommendations to help Netflix improve its content strategy, particularly in terms of expanding TV shows, increasing international content, and diversifying genres.


This project aims to support Netflix’s mission to offer diverse, high-quality entertainment to its global user base by uncovering trends and opportunities that can enhance its content offering and drive continued growth.

# :green_book: **Tools :**


 - **EXCEL**


# :green_book: **Understanding data :**


- **Show_id-** unique id for each tv shows and movies. 


- **Type-** it is TV show or Movies.


- **Title-** Title of tv shows and movies.


- **Director-** director of movies.


- **Cast-** cast of the tv shows and movies.


- **Country-** where the tv shows or movie produced.


- **Date-added-** Date at which the tv shows or movie added.


- **Release year-** year at which the tv shows or movies released. 


- **Rating-** Rating of the tv shows and movies.


- **Duration-** Duration and Seasons.


- **Listed_in-** Genre of tv shows or movies.


- **Description-** Description of movies or Tv shows.



# :green_book: **Business Questions :**



**Question 1 : Percentage of Movies and TV shows ?**


**Question 2 : Total number of tv shows and movies per year ?**


**Question 3 : Top 5 actors of movies and tv shows ?**


**Question 4 : Top 10 countries of movies and tv shows ?**


**Question 5 : Top 10 genre of movies and tv shows ?**


**Question 6 : Top 10 directors on Netflix ?**


**Question 7 : Does Netflix has more focus on tv shows than movies in recent years ?**





# :green_book: **Data Cleaning and Wrangling :**



- **1 ) Removing duplicates :**
  
  - There are no duplicates in this dataset.



- **2) Checking spelling :**
  
  - There are some spelling mistakes in the countrycolumn(United states, Hong Kong, Ireland.)



- **3) Trim the data :**
  
  - Trimming the data with whites spaces and replaced with cleaned data.


 
- **4 ) Removing null values :**

  - deleting the null values columns.



- **5)Deleting unknown data :** 

  - Some of the columns with title with name.  consistent with data format wrong like data and decimal .

   
- **6 ) Find and replace :** 

  - Finding the unreliable data , replacing the data with cleaning data.



# :paperclip: **Business Question Solutions :**


### :paperclip: **Question 1: Percentage of Movies and TV shows ?**

###  **Solution :**   
**Observations :** 


- Movies make up 70% of Netflix's content, while TV shows account for 30%.

**Insights :** 
- Netflix focuses more on movies than TV shows, showing a heavier investment in the film catalog.


**Recommendations :** 
- To appeal to viewers who prefer binge-worthy content, Netflix should consider expanding its TV show library, balancing both content types for different audience preferences.


### :key: GRAPH


![Screen Shot 2024-04-12 at 12 50 34 AM](https://github.com/Sumit-Baviskar/Netflix-Excel/assets/153518735/2f34ba65-06e1-4e91-a6d5-b1020b5c8369)


------------------------------------------------------------------------------------------------------------------------------------------------

### :paperclip: **Question 2 : Total number of tv shows and movies per year ?**

###  **Solution :** 

- **Observations :**

  - The number of movies and TV shows added per year has risen significantly since the mid-2010s.


- **Insights :**
  
  - Netflix’s aggressive content acquisition and production strategy has been especially evident in recent years, leading to a sharp growth in content.


- **Recommendations :** 

  - Netflix should maintain its pace of content production and acquisition while diversifying content genres to cater to broader viewer preferences and keep the growth sustainable.

### :key: GRAPH

![Screen Shot 2024-04-12 at 12 49 49 AM](https://github.com/Sumit-Baviskar/Netflix-Excel/assets/153518735/9f4c28b6-7a2f-42d6-ba3d-2321d5d17308)


------------------------------------------------------------------------------------------------------------------------------------------------
### :paperclip:  **Question 3: Top 5 actors of movies and tv shows ?**

###  **Solution :**

- **Observations :**

  - David Attenborough appears in the most Netflix titles (19), followed by other prominent actors such as Vatsal Dubey and Samuel West.


- **Insights :**

  - The popularity of David Attenborough suggests that documentary content has strong appeal on Netflix.


- **Recommendations :**

  - Netflix should continue investing in documentary series and leverage popular figures like Attenborough to create more educational, nature-focused, or informative content to attract a wider audience.


### :key: GRAPH

![Screen Shot 2024-04-12 at 12 49 08 AM](https://github.com/Sumit-Baviskar/Netflix-Excel/assets/153518735/86696842-69b4-4ea9-bf21-f236bbfe861d)



------------------------------------------------------------------------------------------------------------------------------------------------

### :paperclip: Question 4: Top 10 countries of movies and tv shows?

###  **Solution :**


- **Observations :**

  - The United States (2,818 titles) and India (972 titles) lead in Netflix content production, followed by countries like the UK, Japan, and South Korea.


- **Insights :**


  - The content library is dominated by productions from the US and India, suggesting potential gaps in representation from other regions.


- **Recommendations :**

  - Netflix should further expand its global content offerings by tapping into underrepresented regions such as Africa, Latin America, and the Middle East to increase its global appeal.


### :key: GRAPH



![Screen Shot 2024-10-04 at 12 52 20 AM](https://github.com/user-attachments/assets/f08ede78-4816-431c-a124-49e77c0241f9)


------------------------------------------------------------------------------------------------------------------------------------------------

### :paperclip: **Question 5: Top 10 genre of movies and tv shows ?**


###  **Solution :** 


- **Observations :**

  - "Dramas, International Movies" lead with 362 titles, followed by "Documentaries" and "Stand-Up Comedy".


- **Insights :**

  - The strong presence of documentaries and comedy content indicates that these genres resonate well with Netflix’s audience.


- **Recommendations :**


  - Netflix should continue expanding its offerings in popular genres like documentaries and stand-up comedy while exploring opportunities in niche genres that can differentiate the platform from competitors.


### :key: GRAPH


![Screen Shot 2024-04-12 at 12 48 05 AM](https://github.com/Sumit-Baviskar/Netflix-Excel/assets/153518735/b7461486-7bb0-4c07-8ff3-70c3ed2d992c)



------------------------------------------------------------------------------------------------------------------------------------------------

### :paperclip: **Question 6: Top 10 directors on Netflix ?**


###  **Solution :** 

- **Observations :**
  
  - Rajiv Chilaka and Raúl Campos top the list with 19 and 18 titles, respectively, followed by directors such as Suhas Kadav and Marcus Raboy.

  
- **Insights :**

  
  - The presence of diverse directors in the top ranks indicates Netflix’s commitment to working with international creators.


- **Recommendations :**

  
  - Netflix should continue nurturing relationships with top directors while identifying new talent, particularly from underrepresented regions, to foster a variety of content offerings
  

### :key: GRAPH



![Screen Shot 2024-04-12 at 12 47 23 AM](https://github.com/Sumit-Baviskar/Netflix-Excel/assets/153518735/18b67fc6-b9a4-4152-9913-54e4d2e3f028)


------------------------------------------------------------------------------------------------------------------------------------------------


### :paperclip: **Question 7 : Does Netflix has more focus on tv shows than movies in recent years ?**

###  **Solution :**


- **Observations :**
  
  - Despite the dominance of movies, the production of TV shows has surged in recent years, with both types showing strong growth.

  
- **Insights :**
  
  - Netflix has increased its focus on TV shows, reflecting the rising demand for episodic content and binge-watching preferences among users.


**Recommendations :**
- Netflix should continue balancing its investment in both movies and TV shows, particularly focusing on developing long-running series that can drive sustained user engagement.

### :key: GRAPH

![Screen Shot 2024-04-12 at 12 45 35 AM](https://github.com/Sumit-Baviskar/Netflix-Excel/assets/153518735/3f9620f5-6de8-4618-a3c9-e790d325cf65)


------------------------------------------------------------------------------------------------------------------------------------------------
# :paperclip:  **DASHBOARD :**



![Picture1](https://github.com/Sumit-Baviskar/Netflix-Excel/assets/153518735/175f8050-ee2b-454b-8238-540e2ac72556)





# :paperclip: **Final Recommendations :**


**1 . EXPAND TV SHOW CATALOG :**


  -  While Netflix currently has more movies (70%) than TV shows (30%), TV series have become increasingly popular among viewers, as evidenced by the recent growth in TV show production. Netflix should continue to invest in high-quality TV series, particularly long-running ones that encourage binge-watching and boost subscriber retention.


 
**2 . DIVERSIFY INTERNATIONAL CONTENT :**


  - The United States and India dominate Netflix's content library in terms of production. To attract a broader international audience, Netflix should further invest in content from underrepresented regions such as Africa, South America, and the Middle East. Expanding the variety of international content can enhance global subscriber growth and increase Netflix’s competitive edge in new markets.


**3. LEVERAGE DOCUMENTARIES AND STAND-UP COMEDY :**


  - Documentaries and stand-up comedy rank high in terms of genre popularity, indicating strong viewer interest. Netflix should capitalize on this by continuing to produce high-quality content in these genres. Partnering with popular actors, directors, and comedians can further enhance the appeal of these offerings.

**4 . CONTINUE PARTNERING WITH TOP DIRECTORS :** 


  - Directors such as Rajiv Chilaka and Raúl Campos have made significant contributions to Netflix's content library. Strengthening relationships with these top directors, while also identifying and fostering emerging talent, will ensure a continuous stream of innovative and appealing content. Additionally, collaborations with international directors can bring diverse perspectives and new creative ideas to the platform.


**5. FOCUS ON NICHE AND GROWING GENRES :**


  -  Genres such as stand-up comedy, documentaries, and children’s TV have shown substantial popularity. Netflix can boost engagement by expanding its content offerings in these growing genres. Focusing on  niche areas can attract dedicated viewer segments and enhance content diversity.



**6 . BALANCE BETWEEN MOVIES AND TV SHOWS :**
  -  While Netflix’s movie catalog is vast, the platform should continue its strategic push into TV shows, which have become crucial for retaining users through long-running, episodic content. The platform’s trend of increasing TV show production is a positive move and should continue, ensuring that both movies and series cater to diverse viewer habits



# :paperclip: **Conclusion :**

This project has provided a detailed analysis of Netflix’s content library, offering key insights into the platform's current strategy and areas for potential growth. From the data, it is clear that Netflix has focused heavily on expanding its movie catalog, which makes up the majority of its content offerings. However, the recent increase in TV show production shows that Netflix is responding to audience demand for episodic content, with TV series playing an important role in retaining users through long-form, binge-worthy content.

One of the key takeaways is that Netflix has a strong presence in major content-producing countries such as the United States and India, yet there is ample opportunity to further diversify its global content. Expanding into underrepresented regions like Africa and Latin America would not only attract new audiences but also broaden Netflix’s cultural reach. Additionally, popular genres such as documentaries and stand-up comedy are performing well, suggesting that Netflix should continue to invest in these areas while also exploring niche genres that could differentiate it from competitors.

Overall, the analysis indicates that Netflix is on the right path, especially with its increasing focus on TV shows and documentaries. However, to stay ahead in an increasingly competitive market, Netflix must continue to adapt by diversifying its content geographically and genre-wise, maintaining strong relationships with top directors and actors, and keeping up with the growing demand for original, long-form series. The recommendations provided offer a roadmap for Netflix to further enhance its content strategy and maintain its position as a global streaming leader.










