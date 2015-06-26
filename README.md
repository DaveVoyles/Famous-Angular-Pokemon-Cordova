# Famous-Angular-Pokemon-Cordova
### Author(s): Dave Voyles | [@DaveVoyles](http://www.twitter.com/DaveVoyles)
### URL: [www.DaveVoyles.com][1]

Sample project for using Famo.us + Angular to create a mobile application
----------
### Objective

- *[View the project in your browser](http://famous-angular-pokemon.azurewebsites.net/app/#/)*
- *[Tutorial for the web portion of the project](https://github.com/DaveVoyles/famous-angular-Pokemon/blob/master/README.md)*

I love high performance JavaScript, and have faith that others will finally come around and understand its true potential someday too. Famo.us allows you to maintain a silky smooth 60 Frames Per Second while having fluid animations on screen. Famo.us does this by utilizing the CSS3 primitive -webkit-transform: matrix3d, which lets the framework compute the composite matrix and skip the browser’s renderer. No plug-in, no download, no hack. By appending this to each DIV, developers can render the composite matrix and go straight to the GPU. 

I go more in depth when discussing the ins-and-outs of Famo.us in an [earlier blog post.](http://www.davevoyles.com/creating-a-mobile-app-with-famo-us-and-manifoldjs/) Thanks again to [Zack Brown](https://twitter.com/zackaboo) for all of your assistance with this!

### By the end of this project you will be able to:

- Understand how Angular works within the context of a Famo.us application
- Harness the true power of JavaScript and the good parts of HTML5
- Create smooth animations 

My goal for this project to illustrate how easily you can create HTML5 / JS projects which work at near native speeds on mobile applications. 

### Features
 - The mobile applications runs on iOS and Android via Cordova
 - The Win 10 app runs natively on Win 10
 - This project can also be run as a standard website, although I have it scaled best for mobile devices


### Requirements
- Mac (OS X)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Cordova](https://cordova.apache.org/docs/en/4.0.0/guide_cli_index.md.html) 

You could also do this on Windows just as easily using [Visual Studio tools for Cordova.](http://www.davevoyles.com/apache-cordova-integrated-visual-studio-multi-device-hybrid-app-development/) 


### Setup
 1.  Download the source from [GitHub](https://github.com/DaveVoyles/Famous-Angular-Pokemon-Cordova)
 2.  Install the [Git Command Line Iterface (CLI)](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
 3.  Install [Xcode](https://developer.apple.com/xcode/downloads/)
 4.  Install the [Cordova CLI](https://cordova.apache.org/docs/en/4.0.0/guide_cli_index.md.html) 
 
 **NOTE:** You can find the project this is based off of (w/ out the Cordova stuff) [here.](https://github.com/DaveVoyles/famous-angular-Pokemon)

### Opening the project
1. Start your web server
2. Navigate to **famous-angular-Pokemon/app/**

The project is designed to work on mobile devices, so use the mobile emulator in your browser to get the correct view. Here's what it would look like on an iPhone 6 inside the emulator via the Chrome desktop browser (375x667):

![](https://dl.dropboxusercontent.com/s/23x36anflarivuf/Screenshot%202015-06-24%2015.22.24.png?dl=0)
![](https://dl.dropboxusercontent.com/s/lh66rbv4b413bx9/Screenshot%202015-06-24%2015.26.45.png?dl=0)


And here is how it looks in the iOS simulator via Xcode:

![](https://dl.dropboxusercontent.com/s/urj5q6csj3kgtli/Screenshot%202015-06-24%2017.26.03.png?dl=0)
![](https://dl.dropboxusercontent.com/s/u0wlhuyog04b84y/Screenshot%202015-06-24%2017.25.55.png?dl=0)


### Still to do:
Port to other platforms.

---------
