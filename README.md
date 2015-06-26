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
- [Xcode](https://developer.apple.com/xcode/downloads/)
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
### Building Cordova from the CLI
The Cordova website offers some [excellent docs](https://cordova.apache.org/docs/en/4.0.0/guide_cli_index.md.html) on how to do this, but I'll dive into a bit of detail to explain how some of it works. 

The first thing you'll want to do is [download the finished web project from my GitHub repo.](https://github.com/DaveVoyles/famous-angular-Pokemon). From there, we'll need to create the app using the Cordova CLI (Command Line Interface). 

### Creating the app
I'm going to start from the path *Users/DaveVoyles/Documents*. If you aren't comfortable with using the CLI or Terminal in OSX, I'd suggest watching this [6 minute YouTube video](https://www.youtube.com/watch?v=YRuK2cJ9GI4) which provides a great overview and explains some of the terms I'll be using. 

To navigate here you can enter the Change Directory command (cd) in the Terminal, then *drag* the folder you want to start in:

```
cd <drag your folder from the Finder app into here>
```

Then press enter. We are now working out of this folder. We need to make a folder to hold this content, so enter this command first:

```
mkdir FamousCordova
```

This will create a new directory (folder) at our current location and name it 'FamousCordova'. We need to navigate into that folder now, as this will be our starting point for creating the project.

```
cd FamousCordova
```
Let's actually create the Cordova project now: 

```
cordova create PokemonApp PokemonApp
```

It looks like of funny because I entered *PokemonApp* twice, right? The first time, I am creating a project called "PokemonApp". The second time I enter it, I am entering the display title, which is what you see at the top of your app inside of the iOS emulator. This argument is optional. 

![](https://dl.dropboxusercontent.com/s/mcaybz08cks2ndp/Screenshot%202015-06-26%2010.32.16.png?dl=0)

### Adding the iOS platform
We've got our first project! But we still need to add inidividual platforms. Let's add iOS right now. 

First, we need to navigate into the PokemonApp folder:

```
cd PokemonApp
```

Now add the iOS platform:

```
cordova platform add ios
```

![](https://dl.dropboxusercontent.com/s/fiedvrswxkcywgb/Screenshot%202015-06-26%2010.36.39.png?dl=0)

----------
## Resources

- [Famo.us Slackchat ](http://famous.org/support/)
- [BizSpark, for free MSFT dev licenses and web hosting](http://davevoyles.azurewebsites.net/bizspark-free-software-cloud-services-o/)
- [E-mail me with questions](mailto:Dvoyles@microsoft.com "Dvoyles@microsoft.com")

----------

##Change Log
###v1.0.0
Initial build of the app


  [1]: http://www.daveVoyles.com "My website"
