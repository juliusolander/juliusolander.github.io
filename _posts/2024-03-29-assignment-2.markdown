---
layout: post
title:  "Assignment 2"
date:   2024-03-29 10:20:22 +0100
categories: jekyll update
---

Authors: Julius Olander (s203225), Astrid Machholm (s222228) & Diba Afzali (s223104)

---

<figure> 
<img class="article-image" src="/assets/images/crime_development.png" alt="A descriptive alt text">
<figcaption>Figure 1: The plot shows the most occuring crimes from the SF Dataset (the ones exceeding an average of 5000 occurences across 2003-2018). Most crime categories stay stable or are even in slight decline, whereas Larceny/Theft has grown rapidly since 2012. </figcaption>
</figure>


<br/>

<div class="container">
<div class="flex-grid">
  <div class="col">
    <h2 class="article-heading">Larceny in SF</h2>

<span>In recent years, the city of San Francisco has worked hard to lower crime and make the city safer for everyone. The data used in this article is from San Francisco's Police Department, who publishes data on recorded crime incidences, including various descriptors of the crime, such as Category, Description, GPS Coordinates, Address, Time and Date etc. [1]. In the following, we look into the crime development from 2003 to 2018, specifically Larceny, and pose the questions: are the police and politicians of San Francisco doing the right thing to combat rising thefts, and does the current rise in homelessness contribute to the rising crime trend? </span>

<br/>
<br/>


<h3>California's highest rate of theft </h3>

<span>Politicians, the San Francisco PD, and the local communities have gathered in an effort to reduce crime. Their efforts range from increased police presence and predictive policing to addiction treatment and neighborhood watching by local citizens. The data reported by the San Francisco PD shows a slight reduction or steady levels in the number of crimes across the biggest crime categories over recent years. Despite the effort to reduce crime, it doesn't have a significant positive effect on crime rates. Upon inspection, one category with a strong negative development stands out: Larceny and theft (Figure 1).  </span>
Not only is this latency and theft rising, but the San Francisco rates are also well above the California average, as reported by the Santa Clara County District Attorney's Office 10-year analysis of crime trends in California [2].

<br/> 

<br/>  
  
<span>From 2003 until 2012, larceny and theft stayed steady, with roughly 25,000 cases yearly. Since then, the reported incidences have exploded, totaling almost 50,000 in 2017. </span>
   
<span>In the same period, the number of people experiencing homelessness is also growing, and the city is not able to provide sufficient shelter for this growing population group [3]. The few crime categories that have seen a reduction in recent years could likely be due to the efforts in collaboration with the local communities. However, society's most vulnerable people are likely not reachable by such efforts. As one of the main contributing factors to homelessness is poor social status among psychological issues, which can lead to extreme poverty, for some, the only way to gain quick cash is to commit larceny or theft. If the focus of the policy makers is not on the underlying cause of the crime, e.g. low social welfare, lack of mentail health insitutions, shelter and healthcare etc. the current trend is unlikely to reverse as police cannot keep up with the high crime rates anymore. </span>
 

 


</div>


<div class="col">
<h3>Time and place increases risk of theft </h3>
<span>As mostly all of San Franciscos homeless shelters are located in the Central and Tenderloin districts of San Francisco [4], this might be an indication that the high occurences of Shoplifting, Outdoor and Propertry  in the same area (Figure 2) has something to do with the large social gap that is present in such districts. These districts are where tourists, the middle and upper class go to eat, shop and work. These activities mostly occur in the peak working hours, and it is therefore no suprise that this is the times of day where by far the most larceny related crimes occur. Figure 2 and 3 confirm, that the opportunities for quick financial gain through larceny and theft are plenty, when both ends of the socioeconomic population are present in both the same time and place. It is important to state that these crimes are not necessesarily being committed by the homeless, but judging from the matter of fact of the many homeless shelters, both the rich and homeless are both present in these districts, and the evidence of large social inequality is indisputable. This has been shown to be the perfect breeding ground for high crime rates [5]. </span>
<br/>  

<span>The police department's efforts regarding predictive policing might prevent other types of crime. Nevertheless, the distribution of Larceny and Theft would require the constant presence of police all throughout the city and by a police force much larger than the current one. </span>
 
<span>
The San Francisco PD data reports multiple sub-categories of larceny and theft; some are greatly overrepresented compared to others, and the automobile-related theft is responsible for the majority of the growth in instances. As per the Figure 2, it appears there is a correlation between the densely populated areas and larceny. While this is true, it is interesting to note that automobile-related theft is spread throughout all the San Francisco police districts. How this relates to the growing social-economic inequality and homelessness is unexplored in this data analysis and will require further research. What can, however, be said, is that measures must be taken to prevent these crimes.
</span>
 <br/>
<br/>


<h3>Conclusion </h3>

<span>
San Francisco is facing many socio-economic and crime-related problems, and the growing larceny and theft rates are especially concerning. Through the exploration of the crime incidences reported by the police department, we can merely conclude that there is a correlation between the rising larceny rate and homelessness; we cannot accurately judge if there is any causation. Notably, homelessness is a sign of growing general inequality, which other studies [5] have found to be a factor in growing crime rates. The current political and policing efforts are not slowing down the negative growth, as larceny is so largely present and spread throughout the city that it would require a great increase in the police force to sufficiently police the problem. Thus, novel measures must be taken to address the underlying causes in order to turn around the development and make the city safer for all.
</span>

</div>
</div>


</div>

<br/>
<br/>
<figure> 
{% include sf_larcenytypes.html %}
<figcaption>Figure 2: The interactive plot shows instances of 7 main categories of Larceny/Theft derived from the Police descriptions made at the time of reporting the crime. The plot shows only the most recent data from 2017 till mid 2018. As seen on the map, the incidences of larceny and theft are spread across all of San Francisco, intensifying in the most densely populated areas around the police districts Tenderloin and Central. Automobile-related and property theft is distributed throughout the city, whereas all other categories are mostly present downtown. The map is interactive; zoom in and explore and filter for different types of Larceny. </figcaption>
</figure>
<br/>
<figure> 
{% include bokehplot.html %}
<figcaption>Figure 3: The plot shows the distribution of the different Larceny types throughout the day, where categories are normalized so the distributions are easily comparible. As visible in the plot, most Larceny occurs in the daily hours, with very little occurences throughout the night. Automobile-Related Thefts seem to be skewed outside regular working hours, whereas Property theft, Shoplifting, Pickpocketing and Outdoor thefts are peaking midday. Special and Attemped thefts seems to peak around 1 and 13, where such a strange distribution most probably indicates that the time of reporting these crimes not always correlates to the time of the crime actually being committed, due to the way the SF Police report such crimes.   </figcaption>

<br/>
<br/>
<h3>Sources </h3>

[1] https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data

[2] https://countyda.sccgov.org/sites/g/files/exjcpb1121/files/10-Year%20Combined%20CA%20Crime%20Stat%20Report.pdf

[3] https://sfgov.org/scorecards/safety-net/homeless-population

[4] https://shorturl.at/dvBH7

[5] https://www.nature.com/articles/s41598-020-80897-8 


<style>
  .container {
    text-align: justify;
    width:95%;
    max-width:1600px;
    margin:auto;
  /* use 2 col layout */
  }
  .flex-grid {
    display: flex;
    flex-wrap: wrap;
    display: grid;
    grid-template-columns: 1fr 1fr;
  }

  .col {
    /* Add additional styling as needed */
    margin: 0 auto;
    width: 320px;
    
  }
</style>