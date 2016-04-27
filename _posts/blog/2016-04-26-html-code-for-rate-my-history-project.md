---
layout: post
title: "Rate My History Project"
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2016-04-26T15:39:55-04:00
---

[Rate My History](https://ratemyhistory-gmay.c9users.io) was built in a group project with myself and four other 350 classmates.

### What is *Rate My History*? ###
It is a website where historians and other people in the history-related academia field go to rate historical events and/or individuals.
This site will help history students with deciding whether or not they should do a research paper and/or presentation on that historical event and/or person.

### Contributing to Writing the HTML Code for *Rate My History*: ###

I helped with the layout, search, and home page in the HTML for this website.

#### What I learned: ####
1. For the layout page, I worked on the code to make sure that the basic layout was what we wanted and that it looked decent and provided the correct
functionality that this project required.
2. For the search page, even though we didn't get a chance to finish working on this page, I had to find the right template that could work for our search results.
3. For the homepage, I added a carousel of pictures and a table that displayed the historical event and/or person and the number of views it received. I also had to pick pictures for the homepage so that it didn't look bare. I also had to add the search bar to the homepage.

#### Problems that I had: ####
1. Formatting the Carousel. 
--1. For the homepage, adding the carousel was difficult because I had to not only make sure that the pictures and it's description were showing up on the screen but I also had the problem of making sure that the carousel was formatted correctly to the rest of the website.

~~~
<div class="container">
  <br>

  <div id="myCarousel" class="carousel slide" data-ride="carousel">
  <!--Indicators -->
 
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
      <li data-target="#myCarousel" data-slide-to="3"></li>
      <li data-target="#myCarousel" data-slide-to="4"></li>
      <li data-target="#myCarousel" data-slide-to="5"></li>
      <li data-target="#myCarousel" data-slide-to="6"></li>
    </ol>
     <!--Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
    
      <div class="item active">
        <img src="static/images/BostonTeaParty.jpg" alt="BostonTeaParty" width="460" height="345">
        <div class="carousel-caption">
          <h3>Boston Tea Party</h3>
          <p><strong> December 16, 1773. Defying the Tea Act, the Sons of Liberty disguised as Native Americans poured an entire shipment of tea into the Boston Harbor.</strong></p>
        </div>
      </div>
      
      <div class="item">
        <img src="static/images/Waterloo.jpg" alt="Waterloo" width="460" height="345">
        <div class="carousel-caption">
          <h3>Battle of Waterloo</h3>
          <p>June 18, 1815. Napolean Bonaparte was defeated and ended his reign as Emperor of the French.</p>
        </div>
      </div>
    
      <div class="item">
        <img src="static/images/ChristopherColumbus.jpg" alt="ChristopherColumbus" width="460" height="345">
        <div class="carousel-caption">
          <h3>Christopher Columbus</h3>
          <p>"Reached the New World in 1492. Established a permanent contact of the Old World to the New World.</p>
        </div>
      </div>
      
      <div class="item">
        <img src="static/images/ElizabethI.jpg" alt="ElizabethI" width="460" height="345">
        <div class="carousel-caption">
          <h3>Elizabeth I</h3>
          <p>Queen of England and Ireland. Ruled for 45 years.</p>
        </div>
      </div>
      
      <div class="item">
        <img src="static/images/watergatehotel.jpeg" alt="watergatehotel" width="460" height="345">
        <div class="carousel-caption">
          <h3>Watergate Hotel</h3>
          <p>In the office building part of the Watergate Hotel, in 1972 was the Democratic National Committee (DNC) headquarters.</br>
          A group of five men broke into the DNC under (later uncovered) President Richard Nixon.</p>
        </div>
      </div>
      
      <div class="item">
        <img src="static/images/TheJungleSinclair.jpg" alt="TheJungleSinclair" width="460" height="345">
        <div class="carousel-caption">
          <h3><em>The Jungle</em> by Upton Sinclair</h3>
          <p>A book written by socialist Upton Sinclair to promote the idea of socialism. Readers only retained the disgusting allegations about the meatpacking industrys' practices.<br>
          Led to the passage of The Pure Food and Drugs Act of 1906 and the Federal Meat Inspection Act.</p>
        </div>
      </div>
  
    </div>
    
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>
~~~

2. Adding the Search Bar.
--1. Making the search bar took hours to code because I had to make sure that it was formatted into the side menu on the homepage.
--2. The text box had to be the correct height and width and also the submit button had to be a certain height and width. I found a magnifying glass icon to use as the submit button instead of the traditional submit button. I wanted it to stand out and it was difficult to do but I believe that the search box looks pretty good.

~~~
<li class="search">
    <form action = "/search.html">
        <!--border:2px solid white;-->
        <div style="width:215px;height:40px;padding:5px;">
            <input type="text" value="" name="searchengine", placeholder="Search"/>
            <input type="image" src="http://findicons.com/files/icons/2260/iphone_toolbar/26/magnifyingglass.png" width="15" alt="Search">
        </div>
    </form>
</li>
~~~