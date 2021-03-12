# My Garden Manager
 ![Screenshot from 2020-07-07 19-47-44](https://github.com/AndyRama/rails-garden-manager/blob/master/My%20garden%20Manager.PNG)  
 
# Base
Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.

# Manage garden
Movie nomination website created as part of the application process for the Shopify Front-End Developer Internship.
# [🔗 View Deployed Version](http://www.manage-garden.xyz/gardens/new/)

## Table Of Contents
* [The Challenge](#The-Challenge) 
* [My Approach](#My-Approach) 
* [Tech Used](#Tech-Used) 
* [Feature Highlights](#Feature-Highlights)
* [Future Additions](#Future-Additions)

---
## The Challenge

Create a webpage that can search OMDB for movies, and allow the user to save their favourite films they feel should be up for nomination. When they've selected 5 nominees they should be notified they're finished.

### Requirements 
* Simple to use interface.
* The ability search the OMDB API and return a list of movies that show at least the title, release year and a button to nominate them. 
* Search results should only be of movies.
* Updates to the search terms should update the result list.
* If a movie has been nominated already, it's button should be disabled within in search results. 
* Nominated movies should move to their own "Nomination List".
* Movies in the nomination list should be able to be removed.
* Display a banner when the user has 5 nominations.

### Provided Reference Image 
![Reference Image](./readme-assets/reference-image.png)

### Extras
Improvements to design and functionality are allowed to be added in order to highlight passion and skills.

[Back To Top](#Table-Of-Contents)

---

## My Approach 

### 1. Feature list
Using Trello I created a checklist of the requirements and then some initial ideas I had for things to add. This let me keep on top of production against the deadline and quickly capture/prioritize new ideas while I was working. For this site I just used a single card, but for larger projects I would break up tasks into separate card on a larger kanban board. 

#### Key Features
* Ensure user friendly error handling for search
* Give users the option to search for series or movies 
* Create new copy (text) for the design that matches the marketing site
* Create a custom and dynamic responsive layout 
* Add CSS Animations throughout
* Have a winner be selected at the end 
* Create authentication so people can't view the winner page on their own
* Make app into a PWA 
* Have the nomination list persist with Local Storage 
* Show expanded information for nominated films 
* Have nominated films link to their IMDB page
* Use a Loader/Spinner when querying the API for search or nominating 
* Add Open Graph and Twitter assets for sharing to social media 

![Reference Image](./readme-assets/trello-card.png)



### 2 — Research
I knew from the beginning that one of the key areas I wanted to play with was the design and keep it within family of the existing brand. This way the nomination site would have the trust of the Shopify brand and the winner would carry more impact. (Plus I really love the branding and wanted an opportunity to apply it in a project.) 

The first places I checked were the [Shopify marketing site](https://shopify.com/) and the [Polaris design system site](https://polaris.shopify.com/). These were valuable to see what sort of layouts, color and typograpy were used. I also took note of the style of copywriting for main service page headlines and how there was an engaging theme of elements overlaying into other sections, breaking the grid.

I also attended a webinar hosted by Shopify that had 5 panelists talk about the application proccess, but more importantly how they approach design and development at Shopify. Being able to learn the context of projects was really important to them and being in a growth mindset. 4 months as intern goes by fast and they mentioned how important it was to take in as much as possible. 

This webinar helped validate for me that applying the context of the exiting brand would be a good direction and that showcasing the ability to adapt to new tech would also work in my favor. 

### 3 — Creating a new design 
Now that I had a feature list and design direction I leveraged Figma for the next stage of planning. Since I was going to build this application with React, I created a "React Component Flow" that showed what components would be needed and how they would be structured. This also made it easier later on the create the folder structure and quickly brainstorm when a new component was needed. 

Next I created the user interface that was tied to a design system. The design system held styles for typography and colors. It also housed Figma components that were built with Auto Layout and Variants. 

Creating these design assets upfront made the coding a lot easier, as many problem could be identified and solved in this initial stage.

#### [🔗 View Figma Designs](https://www.figma.com/file/XItcce2NssWnRXkztKDhDO/The-Shoppies?node-id=4%3A33)

### 4 — Development 
At this stage I had everything I needed to start coding and the above resources proved helpful throughout development. I decided on building the site in React and use Redux, SASS and CSS Animations to support it. These 3 technologies are all areas I can improve in and I wanted this project to be catalyst for growth, even whether it helps earn the internship or not. 

[Back To Top](#Table-Of-Contents)

---

## Tech Used
* Ubuntu 18.04
* Ruby 2.6.6
* Rails
* Javascript
* HTML/CSS
* ProgreSQL
* Git/Github
* Dot ENV
* Node SASS
* CSS Animations
* CSS Grids
* Flexbox
* Figma
* heroku
* Trello

[Back To Top](#Table-Of-Contents)

---

## Future Additions
* Bug: On firefox the content sometimes causes sideways scrolling for a few seconds. 
* Animation: Currently I hide overflow for the main wrapper, while the green nomination block comes in, then after a second turn it back on. I would like to find a different solution for this in the future. This can take a hit on performance since `overflow` applies earlier in the page rendering process, requiring more resources.
* Sharing: I would like to add a way to share the winner results to social media.  

[Back To Top](#Table-Of-Contents)
=======
# URL  
http://www.manage-garden.xyz/

# About
New application allowing producers to connect to facilitate the home alcohol trade between individuals.

# Technologies used
-Ubuntu 18.04  
-Ruby 2.6.6  
-Rails 6.0.0  
-JavaScript  
-HTML/CSS  
-PostgreSQL  
-Git/GitHub  
-Heroku & New Domain  
