# Assignment 1: Protests
The past few years in the United States, there has been a surge in protests in support of Black Lives Matter, gender equity, and other social issues. In this assignment, you'll work with data from [CountLove](https://countlove.org/) -- the same data often [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the New York Times -- to learn more about demonstrations over the past few years. 

By completing the assignment, you will demonstrate the following skills:

- Use of **version control** for managing your code
- Declaring document rendering using **markdown** syntax
- Foundational programming skills in R. 


## Background Research
Before diving into this (or any) dataset, it's important to have _domain familiarity_ (i.e., to know something about the topic). As preparation, I'm asking that you read **three articles** about protests in the U.S., and provide a brief 1 - 2 sentence summary or takeaway from each one. 

In the section below, create an **unordered list** of the three articles you found. Make sure to provide an appropriate markdown link (_not_ just the URL) to the article in addition to your 1 - 2 sentence summary. 

* [About 93% of racial justice protests in the US have been peaceful, a new report finds](https://www.cnn.com/2020/09/04/us/blm-protests-peaceful-report-trnd/index.html)
	+ In this article, the author mentions that about 93% of protests following the death of George Floyd have been peaceful, yet authorities intervened in BLM protests 
	more than other types of protests. Also there were casees in Seattle and Portland where the protests became more violence when authorities interevened, or counterprotests
	that became violent because militias and other nonstate actors intervened.
* [Black Lives Matter May Be the Largest Movement in U.S. History](https://www.nytimes.com/interactive/g2020/07/03/us/george-floyd-protests-crowd-size.html)
	+ In this article, the authors state that when the BLM protests hit its climax in June 6, half a million people participated in protests in almost 550 locations, but that was only one day in a movement that is still continuing today. 
	This article also showed research that about 15 to 26 milion people in the US have once taken part in a BLM protest, and that this number of people would make the BLM movement the protest with the most participants.
* [Armed protests are picking up, and a new study says they're more likely to turn violent](https://www.usatoday.com/story/news/nation/2021/08/23/guns-protests-increase-likelihood-violence/8188602002/)
	+ In this article, the author provides a study that shows that armed protests are more prone to turn violent than unarmed protest, six times more likely to be exact, this study analyuzed more than 30,000 protests in the US over the span of 18 months.
	The study also states that in the research, 1/6 armed protests turned violent while 1/37 unarmed protests turned violent.
## Accompanying Image 
In this section, please **display one image** to accompany your text, and describe _why_ you included it (~2 - 3 sentences). This will require that you download an image into your project folder. In your description, use **bold** and _italics_ (at least once, for practice) to emphasize some of your points. 

!["BML Protest Confronted With Armed Soldiers"](/img/pic.jpg)

## Analysis
At this point, you should open up your `analysis.R` script to begin working with the data. The script will guide you through an initial analysis of the data. Throughout the script, there are prompts labeled **Reflection**. Please write 1 - 2 sentences for each of these reflections below:

- What does the difference between the mean and the median tell you about the *distribution* of the data?  
  
    The difference tells us whether the the data is more distributed towards the higher number or the lower number. The mean is the average while the median is the middle of all the data, if median and mean is equal that means that the data is evenly distributed, if the mean is greater than the median, which is true in this case, then the data is positively skewed, which means more data is distributed on the lower side.
  
- Does the number of protests in Washington surprise you? Why or why not?

    The data number doesn't really surprise me considering what a diverse state Washington is being some part of the state being liberal and other parts of the state being conservative. I believe that this creates a lot of opportunities for people in Washington to protest when there are social events happening since people in Washington could protest to both sides of the issue.
    
- Looking at the `state_table` variable, what data quality issues do you notice, and how would you use that to change your analysis (no need to actually change your analysis)?
    
    I could see that there are some state names that wasn't all capitalized, resulting in duplicate states that should've been counted together. For my analysis I needed to check the states regardless of their cases in order to take into consideration the states that wasn't correctly capitalized.
    
- Does the change in the number of protests from 2019 to 2020 surprise you? Why or why not?

    The change in number of protests from 2019 to 2020 is 6548 protests less, which means that there was less protests in 2020 compared to 2019. This was surprising because of the BLM movements that had occurred and with more people willing to speak up nowadays, it was surprising to see that the numbers of protests had lowered rather than rose.

- Do a bit of research. Find at least *two specific policies* that have been changed as a result of protests in 2020. These may be at the city, state, or University level. Please provide a basic summary, as well as a link to each article.
  
  [Cities and states across the US announce police reform following demands for change](https://www.usatoday.com/in-depth/news/2020/06/18/2020-protests-impact-city-and-state-changes-policing/5337751002/)  
  In this article, it was said that due to the protests, cities and states in the US are starting to reevaluate **police policies**. The most popular change that cities and states began to implement is the ban on chokeholds or neck restraints, but there are also other changes that was also added, such as decreased funding, increased transparency, and required deescalation. This is the **Justice Policing Act of 2020**.

  [House Passes New Bill To Abolish Qualified Immunity For Police](https://www.forbes.com/sites/nicksibilla/2021/03/04/house-passes-new-bill-to-abolish-qualified-immunity-for-police/)  
  In this article, it said that the house passed a New Bill to abolish the **Qualified Immunity** for the police. This means that the local, state, and federal law enforcement officers can no longer be held not responsible for civil rights violations unless the victims can show that their rights were clearly established. Due to the protest about the death of George Floyd, the government passed this bill in order for the police officer who killed George Floyd to be able to be held responsible for his death.

- Take a look (`View()`) your `high_level_table` variable. What picture does this paint of the U.S.?

  From the table, I could tell that the most protests not county the "Other" category would be "Guns" followed by "Civil Rights". This shows that the US is still in a state where the 2nd Amendment is still a big controversy as well as racism since both of those categories were the the two most protested disregarding the "Others" category.

## Critical Reflection
Now that you have had time to work with the data and visualize it, I want you to practice thinking critically about the dataset we provided. An important part of data analysis is reflecting on the assumptions, limitations, and gaps in your datasets. Remember that all datasets have to make assumptions and not all assumptions are bad or unreasonable! Practicing these skill will help you in your career to be self critical and ethically alert.

For this section, please write 2-3 sentences for each of the reflections below:

- How was the dataset collected and who collected the data? 
- What assumptions does the dataset make? List atleast two assumptions you identified. For inspiration, check out this [blog post](https://towardsdatascience.com/check-your-assumptions-about-your-data-20be250c143) that describes one method for identifying data assumptions.   
- What data is missing from the dataset? Think about if there are any data points you would have liked to have seen in the dataset. 

## Final Thoughts
When you are finished, with your analysis, please answer the following questions in 1-2 sentences each. 

- What about the analysis surprised you?
- What parts of this analysis did you find challenging?
- What types of analysis do you wish you were able to do with the dataset, but currently don't have the technical skills to do?
