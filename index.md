## _Abstract_

_In 2013, the Black Lives Matter (BLM) movement emerged in response to the police brutality experienced by Black people in the United States. The movement has become increasingly popular, presumably due to the myriad protests that have been organized since its inception. However, its popularity has sparked mixed sentiment within America’s socio-political landscape. Thus, we analyze how select mediatized protests have impacted discourse and legislative action either in favor of or in opposition to the movement._

## Introduction : Put some vizualizations : pie charts, map, word could... to expose the issue of racism

Alton Sterling, Stephon Clark, or more recently Breonna Taylor and Georges Floyd have tragically become symbols of the struggle against police violence. The US police is indeed often involved in a lot of cases of racial persecution towards minorities, and in reaction, there have been many protests to try to change this constant harassment. According to the Washington Post [1], 918 persons have been shot and killed by police in the past year. By doing a short analysis between 2015 and today with their database and normalizing each killed race by the number of the US inhabitant of the same race, it shows that black Americans are killed by police more than twice as high as the rate for white Americans.
On the right, taking into account only those who are not armed (even not a knife) for questions of legitimacy,  unarmed black people are 3 times more likely to be killed by US police than white people.
The interpretation of these results shows that there is indeed a form of harassment and injustice since black people are much more subject to being shot than white people. 

![Alt Text](unarmed_killings_fast.gif)


![This is an image](killings_over_time.png)
Proportion of killed people per million inhabitants                                                |  Proportion of unarmed killed people per million inhabitants
:-------------------------------------------------------------------------:|:---------------------------------------------------------------:
![This is an image](./photo/armedandunarmed.png)  |  ![This is an image](./photo/unarmed.png)

# Idea of plan

## Global analysis on all the years

### Introducing our dataframe : who are our speakers ?

**Add some pie charts of the speakers.**

[This is an image](./photo/gender_speakers.png)
[This is an image](./photo/age_speakers.png)
[This is an image](./photo/party_speakers.png)

Not surprisingly, the proportion of males in our speakers is much higher than other genders, however, in the US men are yet not more numerous than women for example. One explanation could be that they are more likely to talk to the press, or maybe they are taken more seriously than other genders. The topic of police brutality does not make an exception, as it is mosly discussed by males. 





### Their lives matter

There have been many unlegitimate police killings, some have been mediatized while others have been hidden under the carpet. We do not consider those last cases less important than the more mediatized death, but for a better analysis we chose to focus on people that tragically became famous after beeing unlegitimately killed by police. 

Using entity recognition and crossing it with word clouds, and our knowledge of US events, we have been able to isolate the deaths that impacted the most the American population, and whose names are most present in the dataset. This gives us the following list of sadly famous people, associated to the date on which they were killed : Walter Scott, Sandra Bland, Philando Castile, Alton Sterling, Terence Crutcher, Stephon Clark, Botham Jean, Jordan Edwards. We adde dto this list the name of Colin Kaepernick and associated it with the date on which he knelt at the start of NFL games to protest against police brutality. Indeed, this act was very meaningful for the BLM movement. 

[This is an image](./photo/big_names.png)

Here are all the occurrences of quotations talking about the BLM movement and police brutality, on top of which we can see the dates at which the most mediatized victims of police abuse died, and also the protestation of Colin Kaepernick. It clearly appears that the pic in occurrences of our topic matches those dates.

The quotations we had were only covering the years from 2015 to 2020. Nevertheless, victims of police violence did not start in 2015. And some tragic victims of racism that died in the years before 2015 still have an impact today. For example, the filtered dataset is refering a lot to Trayvon Martin, a young boy killed in February 2012 and whose killer was never charged with murder. His name is specifically mentionned in the days following the particular dates we selected. 


[This is an image](./photo/occurrences_martin.png)



We expect a negative correlation between the number of quotations and the number of days elapsed since the last unlegitimate fatal police shooting. Indeed, the closer to the event, the more quotations we expect. (Pearson's correlation)

We also expect that ther would be more quotations after than before such an event. (Relative increase in the number of quotations)

Make vizualizations on the impact : who reacts the most to the deaths ?


### Sentiment analysis

Plotting the distribution among gender, age or party for particular sentiment scores.

Regression analysis to see also the influence of the different features on the sentiment score. 


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ClaraLeDraoulec/BLM-Data-Story/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Test 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ClaraLeDraoulec/BLM-Data-Story/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
