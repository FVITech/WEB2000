1. How do we measure the length of the critical rendering path?  
  1. The number of server round trips your page must do in order to fully load and render  
  2. The number of actions the browser must take (eg run js, build cssom, build dom, etc) in order to fully load and render your page  
  3. By counting the number of all external resources that must be loaded  
  4. By counting the number of render-blocking external resources that must be loaded  

2. What are the events in the Timeline pane which show the DOM being built, the CSSOM being built, and the render tree being built?  
  1. Parse HTML, Parse CSS, Layout  
  2. Parse HTML, Recalculate Style, Layout  
  3. Parse HTML, Recalculate Style, Paint  

3. What is the render tree?

4. What are three things you can do in order to speed up a website's load time?

5. What is the name of the Google tool you can use to see a list of things you can do to improve your page's load speed?

6. Build an audiobook player that is capable of loading an audio file and that remembers the audio file that was loaded and the location where you left off (using localStorage). You may consult the video project we did in class. You may test your audio player with these files:  
  * http://swolebrain.com/GrowthHackerMarketing.mp3  
  * http://swolebrain.com/TheArtofLearning.mp3  
  * http://cdn.panoply.fm/PP3692963319.mp3  

You need to implement the speed up and speed down controls, as well as the forward 10 seconds and back 10 seconds controls.
