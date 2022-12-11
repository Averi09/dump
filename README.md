# Project: LOLCode Interpreter
### TEAM JOSHUA GARCIA (T-1L)
#### Zenith Averi V. Cipriano
#### Sebastian M. Villavicencio

# Description
> You are to create an interpreter for the LOLCode Programming Language. The constructs required for the project are discussed [here](https://drive.google.com/file/d/1ooCMhXHBoz_SRve0uTH5VF4Y94habUld/view). The interpreter must be able to analyze each line of the program lexically, syntactically, and semantically.

# Instructions
```
You are required to submit the following for the project:
1. A .zip file (filename: <GroupName>_<section>.zip) which should contain the following:
    a. a text file (filename: contributors.txt) that contains the name of all contributing groupmates;
    b. a folder (filename: source code) that contains all the necessary files needed to run your project; and
    c. a Readme.md file that contains the instructions on how to run your project. This includes the necessary dependencies, along with the instructions on how to install them.
2. Submit your peer evaluation by filling out the form in this link.
```

# Documentation
- You must add screenshots of your work.
    Answer: Included in the user guide.
- What did you add to the code.
    Answer: I added background images and borders to the texts, a scrollbar, changed the heart icon to pokemon balls, put my personal information in list tiles for aesthetic purposes and less work. The bg image on the 'My Profile page' is also a gif.
- How are you able to do the exercise.
    Answer: I searched for youtube videos that can help me understand the codelabs activity. After finishing it, I used it as a base code. I turned the randomly generated lists of wordpairs to pre-determined hobbies. Designed it to my liking and added background images!
- Challenges met while doing the exercise.
    Answer: Since everything in flutter was new to me, it took me almost a week to finish everything because I have to do my research on things that I like to do such as turning the dynamic list of wordpairs to a static list of hobbies and adding background images and borders to texts. It also took me a while to put my personal information because I couldn't add anymore children on the ListView for the 'My Profile' page because the divided list of chosen hobbies was already a List and it would only accept widgets if I put it in a square bracket. To solve it, I put them in the list during the declaration.
- Happy paths and Unhappy paths encountered.
    Answer: Included in the user guide

:smile_cat: contact your lab instructor if you have any concerns, inquiries or problems in your exercise.

# User Guide (for Testing)
> When you start the app, the first thing you'll see is the homepage named `Your Profile App` where you can choose your hobby/ies to be included in the profile page.

![HomePage](img/home.png)

> When you click the three horizontal lines found on the upper right corner of your screen, you will be redirected to the `My Profile` page where you will find the author's name, student number, and description. Your chosen hobbies will be listed below the text `My hobby/ies is/are:`. The hobbies list is empty since you haven't chosen any hobbies yet. 

![My Profile Page](img/profile.png)

- Unhappy path :expressionless: Since the user haven't yet chosen even a single hobby even though there is a text stating that there should be hobbies listed, not a single hobby is listed.

> Back to the homepage. If you want to choose a hobby or deselect a hobby, you can click the hobby itself, the pokemon ball aligned to it, or the space in between the text and the ball. You can either right click or left click to lock in you hobby. The pokemon ball will turn blue when you select it. If deselected, the pokemon ball will return to its original color gray.

![Sample Clicks](img/choose.png)

- Happy Path :smile: The chosen hobby will be listed when you go back to the `My Profile` page. It is worth noting that the hobbies will be arranged on the order you clicked them. 
![Test Case #1](img/test1.png)

> There are 15 hobbies in total. When you scroll the page, a scrollbar will appear on the right of your screen to let you know when you are nearing the end of the list.

![Scrollbar](img/scrollbar.png)

> If you choose 5 or more hobbies, the `My Profile` page will also be scrollable with its own disappearing scrollbar.

![Scrolled Profile](img/more.png)

You can now enjoy the app! Congrats and have an amazing day :smiling_face_with_three_hearts: 
