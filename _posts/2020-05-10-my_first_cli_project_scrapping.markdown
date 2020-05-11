---
layout: post
title:      "My first CLI project scrapping "
date:       2020-05-10 21:08:02 -0400
permalink:  my_first_cli_project_scrapping
---


### My first project of this course was to built my first web scrapping two levels deep with Ruby. It was challenging, and sometimes felt like there was no way I can resolve errors hidden in my code, but with my classmates help, the problems started to crack one by one.  

### The project was required to have a CLI for interfacing with the application so it can then pull data from an external source with user’s specific input. I was exited to build something that can be customized to individual and interchanged with different needs. For example, I took a long time just to think about which website to use for this website scrapping CLI is wildly applicable. 

### With the work I did in the learn.co everyday I first thought the project was going to be a piece of cake. I thought I could finish my project in just a couple of days. Hours turned to days to just figure out the right class names for the elements I want to grab from the website, my frustration started to grow. That’s when I realized that I had a lot details to learn and to finish the project, I need to brush through the logic behind every single line of the code and to understand what each class does. 

### The main errors that kept showing up had to do with the element that us used for scrapping. For some reason nothing shows up on binding.pry, but when I test it out on the website inspect console using “document.querySelector(‘.class_name’).textContent’ everything seems to be in order. I then used nokogiri to parse my documents it finally make sense of my scrapping !

### Here is my code below…

```def self.scrape_and_make_reviews
    homepage = Nokogiri::HTML.parse(open("https://www.imdb.com/?ref_=nv_home").read)```

### After hours of trial and error resolving, my code seemed to finally work. I am still getting to the habit of the proggraming lifestyle but i gotta say it feels good to actually get it right after so many failures.


### Overall, my whole week was intimidating and overwhelming. The first project doesn’t seem like a lot but I definitely learned  how important  these skills will be for my future career performance. 

