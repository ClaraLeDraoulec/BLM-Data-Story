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

Add some pie charts of the speakers.

Not surprisingly, the proportion of males in our speakers is much higher than other genders, however, in the US men are yet not more numerous than women for example. One explanation could be that they are more likely to talk to the press, or maybe they are taken more seriously than other genders. The topic of police brutality does not make an exception, as it is mosly discussed by males. 


**Normalize the pie charts**

### Sentiment analysis

Plotting the distribution among gender, age or party for particular sentiment scores.

Regression analysis to see also the influence of the different features on the sentiment score. 

### Entity recognition --> introducing the big names

There have been many unlegitimate police killings, some have been mediatized while others have been hidden under the carpet. We do not consider those last cases less important than the more mediatized death, but for a better analysis we chose to focus on people that tragically became famous after beeing unlegitimately killed by police. 

Using entity recognition and wrossing it with word coulds, and the knowledge of Paula living in the US, we have been able to isolate the deaths that impacted the most the American population, and whose names are most present in the dataset. This gives us the following list of sadly famous people, associated to the date on which they were killed : 

### Showing the impact of mediatized and 'famous' death on the occurences of quotations using the relative increase and the Pearson correlation and peak detection

We can see that there are some peaks in the occurrences of quotations a few days after the deaths of the people we have selected.

We expect a negative correlation between the number of quotations and the number of days elapsed since the last unlegitimate fatal police shooting. Indeed, the closer to the event, the more quotations we expect. (Pearson's correlation)

We also expect that ther would be more quotations after than before such an event. (Relative increase in the number of quotations)

Make vizualizations on the impact : who reacts the most to the deaths ?


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
