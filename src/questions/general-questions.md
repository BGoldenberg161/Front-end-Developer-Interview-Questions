---
title: General Questions
layout: layouts/page.njk
permalink: /questions/general-questions/index.html
---

* What did you learn yesterday/this week?  
I have been trying to teach myself graphQl, I see how useful it can be for running queries in a database and think it would be a great addition to nearly any project. 
* What excites or interests you about coding?  
I love the lifelong learning concept of coding. Things are always changing, nobody will ever know it all. This allows for each member of a team to really make a difference with unique skill sets. 
* What is a recent technical challenge you experienced and how did you solve it?  
In my ApartMate project, I was having a hard time sending the data to the backend for put routes. After tearing some hair out, searhing for answers with my Google-Fu I realized that I was unable to send "extra" data with my body parameters inside of a put. I knew I could use params/query in put calls, but that would have taken some a lot of code refactoring. Knowing that you can send extra variables in body with a post call, I simply ran my updates on the backend inside of a post route, rather than a put. 
* When building a new web site or maintaining one, can you explain some techniques you have used to increase performance?  
Specifically for a React App modularizing the components has been the biggest helper for me. Not only saving myself time from not having to rewrite similar code, but also making the code more understandable to a third-party. Planning(wireframing/ERD) was something I undervalued at the start of my career in software. Having a thoughtout roadmap guideline that defines the major requirements up front has been the biggest help while working with teams.
* Can you describe some SEO best practices or techniques you have used lately?  
Balancing Binary Trees  
[SEO Best Practices](https://backlinko.com/hub/seo/best-practices)
DataBase organization and Naming Conventions can also be very important. Trying to keep the data you will use most near the top of the search tree. 
* Can you explain any common techniques or recent issues solved in regards to front-end security?  
I have used a couple of authentication methods, MERN and expressjs sessions with passport. Both of these methods used salt and hash methods to encript the user input before storing it in a database. 
* What actions have you personally taken on recent projects to increase maintainability of your code?  
Commenting my code has been the biggest helper while going back to do maintance. This was another thing I undervalued at the start because code should be readable, but being able to find parts of code without having to read it is more valueable than the 3 seconds it takes to write a comment
* Talk about your preferred development environment.  
I want to work with a team. The ability to bounce ideas off eachother, have someone to talk through problems, etc. is so valuable. But also having an enviornment where employees can sit down and grind away is important otherwise nothing gets done. Having the balance of community and workplace is very important to me. 
* Which version control systems are you familiar with?  
github, box (if that counts), AutoCAD Vault
* Can you describe your workflow when you create a web page?  
On a personal project I like to build the front and back ends together. This way the data I need and the data I am sending are fresh in my mind when building each route. I try to skeleton out the front end early so that I can add the more complicated components at the project builds. This way if I get any input that requires me to change, I don't have to redesign complicated code.
* If you have 5 different stylesheets, how would you best integrate them into the site?  
I would build components that each style sheet applied to. That way when inserting components into others, each carries its unique and correct style. Worst case I would make sure each style sheet was unique so that they didn't interfere when referencing id's or classes
* Can you describe the difference between progressive enhancement and graceful degradation?  
Graceful degradation is the practice of building an application for modern browsers while ensuring it remains functional in older browsers.  
Progressive enhancement is the practice of building an application for a base level of user experience, but adding functional enhancements when a browser supports it.

[more](https://www.sitepoint.com/progressive-enhancement-graceful-degradation-choice/#:~:text=To%20recap%3A,when%20a%20browser%20supports%20it.)
* How would you optimize a website's assets/resources?  
removing unused code, optimizing images by saving as a better file type such as SVG and using sprites for related images
* How many resources will a browser download from a given domain at a time?
Depends on the browser  
Modern browers allow 6 concurent connections  
  * What are the exceptions?  
  Older browers  
* Name 3 ways to decrease page load (perceived or actual load time). 
Loading Screens, Displaying a base page while the other components are loading, optimizing database structures 
* If you jumped on a project and they used tabs and you used spaces, what would you do?  
I would start using tabs. Don't need to rock the boat! Luckily I already am accustomed to tabs. 
* Describe how you would create a simple slideshow page.  
I would use a materialize carosel. Builing the basic structure in html, the style in css, and use javascript to loop through the carosel images. 
* If you could master one technology this year, what would it be?  
GraphQl for sure. The search ease plus time reductions seem to be a very valuable thing. 
* Explain the importance of standards and standards bodies.  
the standards make the work as developers consistant across the board. Without standards collaboration would be nearly impossilbe. Standards bodies simply define the set of standards for each technology. 
* What is Flash of Unstyled Content? How do you avoid FOUC?  
This can be avoided by waiting until the dom content is loaded before rendering a page. 
* Explain what ARIA and screenreaders are, and how to make a website accessible.  
They help people with imparments access the web. Using the alt tags when you can to explain images. 
* Explain some of the pros and cons for CSS animations versus JavaScript animations.  
* What does CORS stand for and what issue does it address?  
Cross-Origin Resource Sharing  
happens when trying to access 2 or more points at the same time. This is to protect user data.
* How did you handle a disagreement with your boss or your collaborator?  
Approach them kindly, preferably with a solution, and be willing to listen to their input to make the solution fit both parties. 
* What resources do you use to learn about the latest in front end development and design?  
Reddit suprisingly cycles through so much information, it is a great spot to see new techs start to be talked about. And from there Google is my best frined. Finding official documentation is always preferable, but w3 and mdn can always help suplment anything that is missing. StackOverflow is a last resort when looking for examples. 
* What skills are needed to be a good front-end developer?  
Soft: teamwork, communication  
Hard: version control, debugging, testing, and obvioulsy the tech to build it(react, html, css, etc...)
* What role do you see yourself?  
Front-end but working closely with backend. I have an understanding of both sides, but I would like more exposure before transitioning into a pure backend or fullstack position.
* Explain the difference between cookies, session storage, and local storage?  
Local storage: stores data on clients computer and can be removed by the user at any time.  
Session storage: data saved only for a session, once a tab is closed, it is gone.  
Cookies: data stored on the server side