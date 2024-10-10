# Introduction: Biodiversity Analysis

<div class="div" style='width: 100%; height: 500px;'>
    <img src="https://images.pexels.com/photos/28848800/pexels-photo-28848800/free-photo-of-colorful-bird-perched-on-mossy-branch.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Biodiversity image from pexels.com">
</div>

In this project we'll interpret data from National Parks about endangered species in different parks. We will look at the conservation status of some species and try to find patterns as to why some species are endangered. The questions we'll be answering are:
<br>
- What is the distribution of conservation status for species?
- What is the distribution of observations for species in different parks?
- Are certain types of species more likely to be endangered?
- Are the differences between species and their conservation status significant?
- Which animal is most prevalent and what is their distribution amongst parks?


## Project scoping 

Whenever performing a data analysis it's important to scope the project in order to get a good grasp of our project goals, analysis and data. Our project goals are simply the main reason we're performing this analysis in the first place and our analysis is simply how we look at our data and extract useful insights that will help better our situation and as for our data it's what we're performing the analysis on provided by (hopefully) reliable sources. 

#### Project Goals
The goal of this project is to interprete data from National parks about endangered species in different parks. This is so that we can tell the park managers what the status of their parks are in terms of species that are endangered and help suggest solutions to better cater for them. 

#### Analysis
Here we'll analyse, clean, visualize and draw insightful conclusions on the data, when analysing we'll focus mainly on endangered species in different and see if there are any patterns as to why they are endangered.

#### Data
This data is provided by [Codecademy]("https://codecademy.com"), although it's fictional it's inspired by real life data. This data consist of 2 csv file `species.csv` and `observation.csv` the `species.csv` data has 5824 rows and 4 columns (variables):


- category: The category of the species
- scientific_name: The scientific or botanical names of the species
- common_names: The common names of the species
- conservation_status: The level of conservation of the species

while our `observation.csv` has 23296 rows and 3 columns (variables)

- scientific_name: The scientific or botanical name of the species
- park_name: The name of the park which the species was sighted
- observations: The number of observations within the last seven days



# Conclusion
Here are the answers to the questions we had in the begining.

- What is the distribution of conservation status for species?
    - The distribution seems to be centered around the `Bird` category being largest `Species of concern`

- What is the distribution of observations for species in different parks?
    - Mostly normal with `Yellowstone National Park` having the highest average of 247 observations in the last 7 days

- Are certain types of species more likely to be endangered?
    - Species that are more likely to be endangered are `Vascular Plant`, `Nonvascular Plant`, `Reptile`,`Fish` and `Amphibian` due to their low proportion of protection

- Are the differences between species and their conservation status significant?
    - More species have significant differences in their conservation status while other don't.

- Which animal is most prevalent and what is their distribution amongst parks?
    - The most prevalant animal would be the `Warbler` bird and it's mostly found on the `Yellowstone National park`


## Futher insights

This data only consist of entries for the past 7 days. Our analysis have revealed some disturbing information about species and how most of them are not protected, our park managers need to really sit up on this, although we don't know who or how the data was collect and exactly why there were a lot of missing entries in the `conservation_status` column in the species dataset. <br><br>
It is worth noting that the proportion of the protected species is alarming, none of the categories of species have more than 17% of it's species protected and what might make it worse is that more species are dependent on one another so endangering one species could affect the biodiversity of others.