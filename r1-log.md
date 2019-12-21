# #100DaysOfCode Log - Round 1 - Melodies

The log of my #100DaysOfCode challenge. Started on [November 26, Tuesday, 2019].

## Pre-Challenge Goals

1. Study Lower Level Language (Cpp)
2. Learn Swift + Simple Swift App (in prep for CS3217) - Hackintosh 
3. Work on UPlan app (Study more on Serverless Framework)
4. DSC Website (Landing - with static site generator/Hugo)
5. Extra: Read up on Functional Programming (Go/Rust)
6. Extra: Revise Operating Systems/Linux (CS Fundamentals)
7. Keep Blog updated (once per week on CS topics)

## Log

### Day 1: Nov 26, 2019
**Today's Progress**: Started Week 1 Intro to Cpp by CS106B. 

**Thoughts:** Post-exam Day 0: Researched about learning Cpp/C and decided on learning Cpp! 
My Goal: To learn more about and apply  fundamentals behind memory allocation and so on. 

**Link to work:** [CS106B](https://see.stanford.edu/Course/CS106B)

### Day 2: Nov 27, 2019

**Today's Progress**: Learnt Git By Concept. 

**Thoughts:** I often just searched Git commands to use without really understanding fully what might each command do. Next up would install a Git visualiser like Git Kraken.

**Link to work:** [Learn Git By Concepts](https://dev.to/unseenwizzard/learn-git-concepts-not-commands-4gjc)

### Day 3: Nov 28, 2019

**Today's Progress**: Finished up CS106B Lect 2 and 3 (Week 1). Installed Qt IDE and setup sample project. Completed Coding Assignment 1. 

**Thoughts:** Cpp seems like a really interesting language - the first week's handout list down a couple of key features of Cpp (in comparison to Java). I can understand better why some say learning Cpp/C will allow you to have a better grasp of what's going on below the hood (e.g. lack of automatic garbage collector for Cpp, means you have to determine when to release memory references).

The annoying thing about CS106B is that it took quite a while to find free access to Qt and to accessing the Stanford standard library which means I have to implement functions like getInteger getRandom etc from scratch for the assignments. Found that the links below helped.

**Links to work:** 
- [Latest CS106B Reference](http://web.stanford.edu/class/cs106b//handouts/overview.html)
- [Updated Reader](http://web.stanford.edu/class/cs106b//handouts/CS106BX-Reader.pdf)
- [Cpp A1](http://web.stanford.edu/class/cs106b//assn/assn1.html)
- [Qt Installation](https://web.stanford.edu/dept/cs_edu/qt-creator/qt-creator-linux.shtml)

### Day 4: Nov 29, 2019

**Today's Progress**: To learn more about GCP and its services, I coded a simple Slack Slash Command Bot to query Google Search. 

**Thoughts:** Still not sure what's the difference between GCP and AWS. Researched a little more, it seems like the biggest reason why AWS is the clear market leader now is due to it being the first to invest in cloud computing? 

**Links to work:** 
- [Slack Slash Bot](https://cloud.google.com/functions/docs/tutorials/slack)
- [AWS vs GCP](https://kinsta.com/blog/google-cloud-vs-aws/)

### Day 5: Nov 30, 2019

**Today's Progress**: Worked on the Typescript React Conversion Guide where I've migrated a JS TicTacToe game into TS compiled with Webpack 4.

**Thoughts:** While this is not the first time I'm working with Typescript, it is the first time I have migrated from pure JS to pure Typescript and it does take a fair bit of time. I feel that this is worth it in the long time though as during the conversion, I actually found a small bug existing inside thr original Microsoft version which is amazing.

**Links to work:** 
- [React Conversion Guide](https://github.com/Happytreat/TypeScript-React-Conversion-Guide)
- [Typescript Handbook](https://www.typescriptlang.org/docs/handbook/migrating-from-javascript.html)

### Day 6: Dec 1, 2019
**Today's Progress**: Configured UPlan to use Webpack 4 on the client. Read up on Chpt 2 of CS106B Reader.

**Thoughts:** Not the first time working with Webpack, but was refreshing to start from scratch and got to explore the newer features of Webpack 4 (as compared to v2x) such as merge. Was a really satisfying feeling when it successfully deployed!

**Links to work:** [Webpack 4](https://webpack.js.org/guides/production/)

### Day 7: Dec 2, 2019

**Today's Progress**: Completed CP106B Lecture 4, learnt about C++ Libraries and the concept of abstraction and interfaces in C. Completed Hacker Tools Lectures on Virtual Machines and Shell Scripting. Finished the day off with some devOps maintenance of project.

**Thoughts:** Watching the HT guys was like a series of "Ohhhh" moments as I finally understood how my supervisors use the command line so efficiently. A really cool trick I've learnt is that the shell can chain and group commands and so a command like

```shell
{who; ps aux} | grep Happytreat | head -n 5
```

would concat the output from who and ps aux, then find those containing 'Happytreat' and output the top 5. Each of these commands only focuses on 1 thing (Unix concept of doing one thing and do it well).


### Day 8: Dec 3, 2019
**Today's Progress**: Completed Reader Chpt 3. Experimented with VirtualBox macOS and docker images.

**Thoughts:** Was pretty busy with DSC stuff preparing for meeting today and definitely wanted to start some refactoring for UPlan. Will have to up the coding pace from now on. 

### Day 9: Dec 4, 2019
**Today's Progress**: Read up on CSS Paradigms, Architecture such as BEM, Sass etc. Refactored UPlan app CSS styles using Styled component with BEM archictecture. Redesigned the layout of UPlan Landing pages. 

**Thoughts:** CSS is really not as simple as most people think (or at least what I once thought). Really excited to try out SASS mixing etc and libraries such as complement(color). 

### Day 10: Dec 5, 2019
**Today's Progress**: Continued with UPlan Refactoring of Styles and components. Added Theme provider and several pastel themes to the app. Also planned additional features to add to UPlan to make the app simple, yet efficient to users (to differentiate from the many attempts at building similar apps).

### Day 10b: Dec 7, 2019
**Today's Progress**: I took a Docker and Kubernetes 3h workshops at Developer space today. Learnt how to build a docker image and run it on a local machine. Learnt how to build a docker network and run multiple containers to interact on the same network.

**Thoughts:** Not counted as a full day of code as most of this is through sample codes/tutorials without much internalising.

### Day 11: Dec 8, 2019
**Today's Progress**: Built up a boilerplate for React Beautiful Dnd components for UPlan and future projects using Dnd. Also setup Eslint Airbnb and setup Webstorm preference for editor etc. 

**Thoughts:** After going through the Egg Head Course, I finally understood the subtlety of the dnd components such as how snapshots provided an additional feature to control what the board looks like when dragging (between cols and within a col). It is also the first time I've used shouldComponentUpdate function to optimise by reducing unnecessary renders.

### Day 12: Dec 10, 2019
**Today's Progress**: Update Personal Website with Newer Projects and Resume. Started Refactoring Drag and Drop Components in UPlan - styles, dnd functions, redux. Refactored Backend Functions for Delete sem, optimise frontend. Started refactoring the serverless functions, separating business logic from the FAAS - enabled me to start unit testing. 

### Day 13: Dec 19, 2019
**Today's Progress**: Just came back from overseas - back to the grind. Refactored the Backend Modules Lambda Function (see Day 12) and added unit tests. Just came across that Jest has the ablity to test DynamoDB, will try that with integration tests next. Also fix the redirect SPA problem in Netlify. It was slightly tricky as I had to place the _redirects text file in the dist folder which was cleaned each time. The solution I used in the end was to copy the _redirects file after cleaning from the public to dist folder. 

### Day 14: Dec 20, 2019
**Today's Progress**: Fix an issue with React / Webpack with loading image relative path dynamically using require. Tried using lazy loading (does not work - to be researched more) and dynamic loading both of which removes the error but does not load the image. In the end, found out that require.context(folder, true) works. Will be researching more about this interesting problem. 

### Day 15: Dec 21, 2019
**Today's Progress**: Created a Persist Theme in UPlan App. Makes more sense to shift theme into the user redux store (global store) so that it persists with the user. 