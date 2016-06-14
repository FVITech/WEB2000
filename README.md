# WEB2000

###Day 1

Html emails. The purpose of this class is for students to understand the challenges in creating html code which is compatible with all email clients. Students will create an email-friendly html resume.  

We go through the contents of the following articles:  
http://webdesign.tutsplus.com/tutorials/what-you-should-know-about-html-email--webdesign-12908  
http://webdesign.tutsplus.com/articles/build-an-html-email-template-from-scratch--webdesign-12770  

Students will start by designing a wireframe of the html email resume they want to create, or picking a template from this site. Their project will be to create an html version of this wireframe with a resume.  

We clarify that external files and fonts cannot be used in emails. Use W3 to go over web safe fonts.   http://www.tutorialspoint.com/html/html_fonts_ref.htm

Inline styles are imperative for emails so students will be shown how to use the mailchimp or inkd css inliners.  

###Day 2

Write a resume auto-emailer portal. It's supposed to post to this node endpoint. Students will create a nice form with the required fields (from, html_file_name, dest_email, subject) and post it to the route at  

http://fvi-grad.com:4004/resume-emailer  

A finished resume from the previous day is required. The student will give his file to the instructor and the instructor will upload it to the server in the correct folder so that the node route picks it up.  

Students must upload their resume emailers to their fvi-grad.com shared web space.  

Sample finished resume with inline styles: http://catmiller.fvi-grad.com/Web-Resume/cathy.html  

Sample resume emailing form: http://catmiller.fvi-grad.com/Web-Resume/emailForm.html (students should be encouraged to make it nicer looking)  

###Day 3

Intro to HTML canvas. Students will learn how to draw an image on a canvas and how to use requestAnimationFrame to create animations. We teach this, as well as keyboard events, through creating a project with a videogame character that reacts to movements and moves around a canvas containing a background image. Example:   

https://github.com/Swolebrain/simple-html5-canvas-mario

###Day 4

HTML canvas portfolio item. Students will create a landing page using a staticly positioned canvas as a background, like this one: http://fvi.edu/portal-concept/

Instructor should encourage students to pick their own background image and gradient, teach the students how to make the background image scroll, teach the students how to match the background color of the body to the gradient, and teach the students how to position things with javascript. Students must be encouraged to pick their own two icons and seamless texture by using google image search (and using search tools to filter based on size and usage rights) or by using these free image sites:  
http://thestocks.im/  
http://negativespace.co/  
https://unsplash.com/  
http://www.pexels.com  

Really good students should feel free to incorporate any of the stuff on threejs.org into their landing page and make something like explore.fvi.edu/lp3d  

Absent students on either day 3 or 4 can follow the meme generator course from udacity.  

###Day 5  

Introduction to the new HTML5 semantic elements. By the end of this class students will know how to use the nav, article, and section elements, as well as audio and video components. Students will also review how to use the localstorage construct. Web workers and web app resource loading will also be mentioned but not applied (ch25 of php book). We follow this resource: https://www.pluralsight.com/courses/semantic-html-2329    

###Day 6  

Introduction to video and audio elements. We went through the first 3 parts of the treehouse class and made the two pages in this repo: https://github.com/Swolebrain/html5-video-and-audio-demo

###Day 7  

The objective of this day is for students to understand the principles of html performance optimization. After this class, students will have learned and applied asynchronous loading of scripts, conditional resources dependent on media, optimization of images, and minification of resources. Students will be assigned a project where they will implement a simple board game.

###Day 8  

Students will learn about CSS transforms and transitions, and then use the knowledge to continue working on their board game and implement the movement of the game pieces.

###Days 9  

Responsive Web Design Fundamentals. Being one of the most important skills in the labor market for front end web developers, responsive web design is given a thorough introduction. Students will learn how to use media queries in order to alter the look and feel of their site according to the device it is viewed in and will build their own framework for a bootstrap-like responsive grid.

Intro to media queries http://www.w3schools.com/cssref/css3_pr_mediaquery.asp  
Then go into details with the media features: https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries  
Creating printer friendly pages with media queries: https://benfrain.com/create-print-styles-using-css3-media-queries/

###Day 10  

Canvas game development basics. We create a game of Pong and show students how to create a scrolling background with parallax.

###Day 11  

Put canvas knowledge to work by creating a Flappy Bird clone.

###Day 12  

Conceptual final exam and additional time to finish Flappy Bird Clone.
