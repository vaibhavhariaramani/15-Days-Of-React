# 15-Dyas-Of-React
15 Days of React challenge is a step by step guide to learn React in 15 days


<sub>Author: <a href="https://www.linkedin.com/in/vaibhav-hariramani/" target="_blank">Vaibhav Hariramani</a><br>
<small> October, 2020</small></sub>

</div>

[Day 1 >>](./01_Day_JavaScript_Refresher/01_javascript_refresher.md)

| # Day |                                                           Topics                                                            |
| ----- | :-------------------------------------------------------------------------------------------------------------------------: |
| 00    | [Introduction](#introduction)<br> [How to Use Repo](#how-to-use-repo)<br> [Requirements](#requirements)<br> [Setup](#setup) |
| 01    |                      [Todo_without_Redux](./01_Todo_without_Redux/01_Todo_without_Redux.md)                       |
| 02    |                     [Todo_with_Redux](./02_Todo_with_Redux/02_Todo_with_Redux.md)                     |
| 03    |                                     [Netflix_clone](./03_Netflix_clone/03_Netflix_clone.md)                                      |

🧡🧡🧡 HAPPY CODING 🧡🧡🧡

<div>
<small>Support the <strong>author</strong> to create more educational materials</small> <br />  
<a href = "https://www.paypal.me/asabeneh"><img src='./images/paypal_lg.png' alt='Paypal Logo' style="width:10%"/></a>
</div>

---

- [Introduction](#introduction)
- [Requirements](#requirements)
- [How to Use Repo](#how-to-use-repo)
  - [Star and Fork this Repo](#star-and-fork-this-repo)
  - [Clone your Fork](#clone-your-fork)
  - [Create a New Branch](#create-a-new-branch)
  - [Structure Exercise Solutions](#structure-exercise-solutions)
  - [Commit Exercise Solutions](#commit-exercise-solutions)
  - [Update your Fork Daily](#update-your-fork-daily)
- [Setup](#setup)
  - [Install Node.js](#install-nodejs)
  - [Browser](#browser)
    - [Installing Google Chrome](#installing-google-chrome)
    - [Opening Google Chrome Console](#opening-google-chrome-console)
    - [Writing Code on Browser Console](#writing-code-on-browser-console)
      - [Console.log](#consolelog)
      - [Console.log with Multiple Arguments](#consolelog-with-multiple-arguments)
      - [Comments](#comments)
      - [Syntax](#syntax)
    - [Arithmetics](#arithmetics)
  - [Code Editor](#code-editor)
    - [Installing Visual Studio Code](#installing-visual-studio-code)
    - [How to Use Visual Studio Code](#how-to-use-visual-studio-code)

---

## Introduction

**Congratulations** on deciding to participate in 30 days of React programming challenge. In this challenge you will learn everything you need to use to develop a React application. In the end of the challenge you will get a 30DaysOfReact programming challenge completion certificate. In case you need help or if you would like to help others you may join the [telegram group](https://t.me/thirtydaysofreact).

**A 30DaysOfReact** challenge is a guide for both beginners and advanced JavaScript and React developers. Welcome to 30 Days Of React. React is a JavaScript library. I enjoy using and teaching React and I hope you will do so too.
In this step by step 30 Days React challenge, you will learn React which is one of most popular user interface JavaScript libraries.
React can do everything that JavaScript can do. React can be used **_to add interactivity to websites, to develop mobile apps, desktop applications, games_**.
I believe you will learn quite a lot in the next 30 days and your programming and problem solving skills will also be improved significantly.

I will use conversational English and less jargons to write this challenge. The content will be continuously updated. If you find a typo or grammar mistakes don't be surprised because I don't do any proof read before I publish it. I would recommend you to focus on the main message of the challenge instead of the English and some minor mistakes. I really appreciate if you send me pull requests for improvement and remember to pull first from master before you send pull requests. Most of the images I have used in this challenge came from 30DaysOfJavaScript challenge therefore you may need to rename file names and folders 30DaysOfReact.
If you are good at arrays, loops, functions, objects, functional programming, destructuring and spreading and class then you will be able to follow the challenge properly. Otherwise, I strongly recommend you to check [30DaysOfJavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript).

Before you dive into this course, you may check the [review](https://t.me/thirtydaysofreact/992) of 30 Days Of React.

## Requirements

To get along with the challenge you need to have the following:

1. Motivation
2. A computer
3. Internet
4. A browser
5. A code editor
6. HTML, CSS and JavaScript intermediate level skill

## How to Use Repo

### Star and Fork this Repo

Star this repo to support this work and Fork the repo to create your own copy to work from.

### Clone your Fork

You should always work directly from your forked copy.

```bash
# note that an `ssh` link is used here, but an `https` link will work the same
git clone git@github.com:username/30-Days-Of-React.git
cd 30-Days-Of-React
```

### Create a New Branch

To complete daily exercises, my suggestion is to create a separate branch to house your exercise folder or any other changes you make. This will keep your master branch clean at all times, which means your master will always be similar to the original master.

```bash
git checkout -b exercise-solutions # `-b` creates the branch if it does not exist
```

### Structure Exercise Solutions

In your new branch, you can use files/folders to structure your solutions to daily exercises

```bash
mkdir -p solutions/day-01 # `-p` helps create nested directories
touch solutions/day-01/level1.js # touch creates a file
```

### Commit Exercise Solutions

Commit your solutions to your Fork

```bash
git add solutions/day-01/level1.js
git commit -m "chore: exercise level1 complete"
git push origin exercise-solutions # branch `exercise-solutions` was created earlier
```

### Update your Fork Daily

This repo will be updated daily throughout the month. When a new day's content becomes available, you can update your forked copy with the steps below.

```bash
# 1. switch to master branch
git checkout master
# 2. check if your local copy has a link to original `...Asabeneh/30-Days-Of-React.git`
git remote -v
# 3. if not, add a link to original, you can choose any name for the link or use `upstream`
git remote add upstream git@github.com:Asabeneh/30-Days-Of-React.git
# 4. check again to confirm link added
git remote -v
# 5. now you can fetch updates from original repo, assuming you named this `upstream`
git fetch upstream
# 6. merge the updates to your local master branch
git merge upstream/master master
# 7. push the merged updates to your Forked copy on GitHub
git push origin master
```

> Note that the updates are only applied to the master branch. If you wish to update any other branch, repeat steps 6-7 with the branch name. See snippet below for `exercise-solutions` branch

```bash
git merge upstream/master exercise-solutions
git push origin exercise-solutions
```

## Setup

I believe you have the motivation and a strong desire to be a developer, a computer and Internet. In addition to that basic to intermediate level HTML, CSS and JS. If you have those, then you have everything to get started.

### Install Node.js

You may not need node.js right now but you may need it for later. Install [node.js](https://nodejs.org/en/).

![Node download](images/download_node.png)

After downloading double click and install

![Install node](images/install_node.png)

We can check if node is installed on our local machine by opening our device terminal or command prompt.

```sh
asabeneh $ node -v
v12.14.0
```

When making this tutorial I was using node version 12.14.0, but now the recommended version of node.js for download is 12.17.0.

### Browser

There are many browsers out there. However, I strongly recommend Google Chrome.

#### Installing Google Chrome

Install [google chrome](https://www.google.com/chrome/) if you do not have one yet. We can write small JavaScript code on the browser console, but we do not use the browser console to develop applications.

![Google Chrome](images/google_chrome.png)

#### Opening Google Chrome Console

You can open Google Chrome console either by clicking three dots at the top right corner of the browser, selecting _More tools -> Developer tools_ or using a keyboard shortcut. I prefer using shortcuts.

![Opening chrome](images/opening_developer_tool.png)

To open the Chrome console using a keyboard shortcut. It is good to know the shortcut too as a JavaScript and React developer you will spend much time on a browser console and don't be lazy to open it during development.

```sh
Mac
Command+Option+J

Windows/Linux:
Ctl+Shift+J
```

![Opening console](images/opening_chrome_console_shortcut.png)

# Todo List Without Redux

# Todo List With Redux

# Netflix Clone

#Spotify Clone

# Resources 

[https://sites.google.com/view/geeky-traveller/computer-vision/histogram-of-oriented-gradients-and-object-detection](https://sites.google.com/view/geeky-traveller/computer-vision/histogram-of-oriented-gradients-and-object-detection}



## To learn more about these Resources you can Refer to some of these articles written by Me:-

- [Medium](https://medium.com/geeky-bawa)
- [geeky Traveller](https://sites.google.com/view/geeky-traveller/)
- [Blogs](https://github.com/vaibhavhariaramani/blogs)
- [Youtube](https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)[![Youtube Badge](https://img.shields.io/badge/-Geeky_Bawa-1ca0f1?style=flat-circle&labelColor=d54b3d&logo=youtube&logoColor=white&link=https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)](https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)

### Don't forget to tag us

if you use this repo in  your project don't forget to mention us as Contributer in it . And Don't forget to tag us [Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/),[ instagram](https://www.instagram.com/geeky_baba_/?hl=en),[ facebook](https://www.facebook.com/jayesh.hariramani.3) ,[ twitter](https://www.linkedin.com/in/vaibhav-hariramani-087488186/), [ Github](https://github.com/vaibhavhariaramani) 

============================================================================
# Made with ❤️by Vaibhav Hariramani
#### About me

I am a Machine Learning enthusiast, an Actions on Google, Internet of things, Alexa Skills, and Image processing developer.
I have a keen interest in Image processing and Andriod development.
I am Currently studying at  Chandigarh University, Punjab.

[My PortFolio](https://vaibhavhariaramani.github.io/)
You can find me at:-
[Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/) or [Github](https://github.com/vaibhavhariaramani) .

Email: [vaibhav.hariramani01@gmail.com](mailto:vaibhav.hariramani01@gmail.com)


# Download [THE VAIBHAV HARIRAMANI APP](https://github.com/vaibhavhariaramani/The-Vaibhav-Hariramani-App/raw/master/vaibhav%20hariramani%20app.apk)

# [<img src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/gh-bannner-light.png">](https://github.com/vaibhavhariaramani/The-Vaibhav-Hariramani-App/raw/master/vaibhav%20hariramani%20app.apk) 
<p align='center'>
<a href="https://www.linkedin.com/in/vaibhav-hariramani-087488186/"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/linkedin.png"></a>&nbsp;&nbsp;
<a href="https://twitter.com/vaibhavhariram2"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/twitter.png"></a>&nbsp;&nbsp;
<a href="https://www.instagram.com/vaibhav.hariramani/?hl=en"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/instagram.jpg"></a>&nbsp;&nbsp;
<a href="https://www.buymeacoffee.com/vaibhavJii"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/by-me-a-coffee.png"></a>
<a href="https://wa.me/+917790991077"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/whatsapp.png"></a>&nbsp;&nbsp;
<a href="mailto:vaibhav.hariramani01@gmail.com"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/email.png"></a>&nbsp;&nbsp;
</p>


[<img width="150" align='center' src="https://archive.org/download/download-button-png/download-button-png.png">The Vaibhav Hariramani App (Latest Version) ](https://github.com/vaibhavhariaramani/The-Vaibhav-Hariramani-App/raw/master/vaibhav%20hariramani%20app.apk)

Download [THE VAIBHAV HARIRAMANI APP](https://github.com/vaibhavhariaramani/The-Vaibhav-Hariramani-App/raw/master/vaibhav%20hariramani%20app.apk) consist of Tutorials,Projects,Blogs and Vlogs of our Site developed Using Android Studio with Web View try installing it in your android device.

Happy coding ❤️ .

### Follow me
  
[![Linkedin Badge](https://img.shields.io/badge/-VaibhavHariramani-blue?style=flat-circle&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vaibhav-hariramani-087488186/)](https://www.linkedin.com/in/vaibhav-hariramani-087488186/) [![Instagram Badge](https://img.shields.io/badge/-VaibhavHariramani-e02c73?style=flat-circle&labelColor=e02c73&logo=Instagram&logoColor=white&link=https://www.instagram.com/vaibhav.hariramani/?hl=en)](https://www.instagram.com/vaibhav.hariramani/?hl=en) [![Twitter Badge](https://img.shields.io/badge/-VaibhavHariramani-1ca0f1?style=flat-circle&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/vaibhavhariram2)](https://twitter.com/vaibhavhariram2) [![GitHub Badge](https://img.shields.io/badge/-@Vaibhavhariaramani-24292e?style=flat-circle&labelColor=24292e&logo=github&logoColor=white&link=https://github.com/vaibhavhariaramani)](https://github.com/vaibhavhariaramani) [![Gmail Badge](https://img.shields.io/badge/-VaibhavHariramani-d54b3d?style=flat-circle&labelColor=d54b3d&logo=gmail&logoColor=white&link=mailto:vaibhav.hariramani01@gmail.com)](mailto:vaibhav.hariramani01@gmail.com) [![Medium Badge](https://img.shields.io/badge/-VaibhavHariramani-d54b3d?style=flat-circle&labelColor=d54b3d&logo=medium&logoColor=white&link=https://medium.com/geeky-bawa)](https://medium.com/geeky-bawa) 



## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details

