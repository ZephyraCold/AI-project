

# EasyGrade

Final project for the Building AI course

## Summary

EasyGrade is software for generating random tests and automatic grading. EasyGrade test generator will have an option for genereting random tests where the user will be able to choose fileld, difficulty and length of the test. Teacher will add students and generate a random test for each of them.




## Background

These are just a few most obvious problems that my idea solve:

* problem of cheating on tests
* saves time for both making and grading tests
* ecological perspective - no more printing, all the solved tests wil be saved at individual students account
* students will have the oportunity to practise and prepare for the exam  

Problem of cheating is very common among the students, this way all of them will have diffrent problems to solve so at least they want copy answers from one another. Making tests is also extremly time consuming for the teacher and this way the could have more time for lesson planing.
My personal motivation is that I'm also a theacher and its very challenging to test students knowledge online during the pandemic. My topic is intresting because children and their education is one of the most important challenge in the world


## How is it used?

The techer and students will make their accounts (student and techer account). The techer will then add her students inside the group and select date and time of the test, field that will be tested (for example - Physics -> Dynamics -> Work, energy and power -> choose students or group -> generate random tests), difficulty and time. This software would be great for online classes but also for the use inside a class.



Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Data is coming from the database for the assigments, and later the data will be collected upon completed tests and generate statistics about particular problems that students solve well, or not well. From this information teacher can modify their lessons and focus on things that are students strugling with.

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
