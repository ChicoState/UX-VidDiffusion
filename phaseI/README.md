# Phase I: Analyzing Users, Competitors, and Initial Designs

## Introduction

### VidDiffusion
### Team Members: Clemens Strigl, Sabas Martinez, and Cy Baca
VidDiffusion plans on revolutionizing the film making industry for small production studios and even self employed content creators.
This project's aim is to create a piece of software that lets the user apply AI modifications based on prompt to video files. The software must be simple to install and use for someone who has little familiarity with Stable Diffusion and little technical skills to get it installed and running.

## Methods
We have employed competitive analysis, Heuristic Evaluation, and User driven Scenarios and stories to determine the industry standards and common practices for our project type. This gave us great insights into what other companies in our industry are doing and even what features and designs they are lacking according to our business model. Using Heuristic Evaluation we were able to closely determine pros and cons of competing applications while user stories give great insight into who will use our application and what they are trying to achieve.

### Competitive Analysis
In our competitive analysis, we researched potential competitors to our software and evaluated their strengths, weaknesses, the overall quality of the product, price, and platforms that they are available on. After completing the analysis, we came up with four competitors: Stable Diffusion, ControlNet-M2M, Mov2Mov extension for Stable Diffusion, and runwayml.com. Using this method, we were able to come up with a baseline of what we want our product to achieve, as well as understand what we need to do in order to be a viable competitor to alternative software.

### User Stories
We came up with four user stories in order to come up with an idea of what types of people may find use for our software. This gave us insight on what type of functionality we need to make available as well as ideas of what type of interface we want to implement to make the software easy to use for different types of users.

### Heuristic Evaluation
We did a heuristic evaluation on app.runwayml.com using Nielsen's usability heuristics. For each of 10 heuristics, we gave the product a score from 1 to 10 and provided an explanation for the score. The specific heuristics that we evaluated the software on were:

* Visibility of System Status
* Match between system and the real world
* User control and freedom
* Consistency and standards
* Error prevention
* Recognition rather than recall
* Flexibility and efficiency of use
* Aesthetic and minimalist design
* Help users recognize, diagnose, and recover from errors
* Help and documentation


### Personas and Scenarios
We created three personas, each with different backgrounds, lifestyles, and goals, and created scenarios for each of them in which they could use our product to make their job or project easier. They ranged from an accountant that has minimal video editing skills and equipment who wants to make youtube content, to a middle aged content creator with some equipment and skills, to a small video editing studio artist who wants to create an episodic animated series. Each person will need to use the software to accomplish their varying goals.



## Findings

<!---
!!! For each research method, detail each of the findings point-by-point to clarify new discoveries of users' needs !!!
--->
### Competitive Analysis
Upon conclusion of our competitive analysis, we discovered four major competitors: Stable Diffusion, ControlNet-M2M, Mov2Mov extension for Stable Diffusion, and runwayml.com. Stable Diffusion on its own does not pose a major threat as a competitor, because it is very difficult to set up and get running for the average person. However, there is a webui script available from the creator of stable diffusion that makes installation a little easier, and makes access to extensions like Mov2Mov easy to install. It's major fault, though, is that there is still no simple way to install and make video editing available in a few easy steps.
Scripts like ControlNet-M2M and Mov2Mov are difficult to install and run without a certain level of technical ability.
The biggest competition, by far, was runwayml. They have a beautiful user interface, and can produce movies in a few simple steps. However, the software is not installable locally, and it requires subscription to use and payment to produce any video of significant length.
* Users should be able to install the software easily.
* Users should be able to drag and drop files into the interface.
* Users should be able to type a description and click a button to convert easily.
* The software should be easy to navigate.

### User Stories
We came up with four user stories. The stories involved small businesses who want to make advertisements in the form of a video, maybe to be used as a youtube or local cable network advertisement, small video production studios, and social media influencers.
* The software will be used by regular people with video production skills ranging from none to middle.
* The software should be intuitive enough for someone with no knowledge to produce something with decent quality.

### Heuristic Evaluation
The heuristic evaluation gave us good insight on what our competitors were doing right that we needed to implement on the same level or better, but also on what our competitors were lacking on that we could improve upon. The runwayml app was easy to use and efficient. A few possible improvements we found were
* Make the user interface a little bit simpler, possibly with hidden options for advanced users.
* Offer the ability to pause or stop the video conversion process in case of an input error or some other reason.
* Offer recovery for lost or accidentally deleted footage.
* Offer a history of previous prompts, or possibly create a menu that aggregates recent or popular prompts by other users of the software.
* Offer a recently used/modified video field.

### Personas and Scenarios
Through our creation of personas and scenarios we discovered that it is important for our software to be easy to use for people with little or no video editing experience to get good results, but also versatile enough that an advanced user can integrate it into their workflow or alongside other types of video editing software.
* The software should be easy to use for people who have little to no skills.
* The software should be easy to use alongside other types of video editing software.
* The software should be simple enough for someone to upload a video and modify it in a unique way.
* The software should also offer more complex video editing options for people with a higher degree of video editing skill.

## Conclusions

In conclusion, through competitive analysis we have determined that there are no good, easy learnable, easy to install, local applications that employ video diffusion. Either they are an extreme hassle to install or they all require a fast internet connection to upload your files. Additionally, through heuristic evaluations we have determined that in order to appeal to a very high level audience, we will have to implement a very simple and intuitive UX in order to have the shallowest learning curve and the fastest mastery of the tool. Instead of simply displaying configuration numbers, we will incorporate sliders and other neater UX designs to make the user experience more pleasant and efficient.

## Caveats

The biggest caveat that we encountered was that we were not able to actually interview or talk to people that would realistically be our audience. This greatly limits us on what such users want for features since they might be looking for a tool with specific but important specifications. Secondly, all evaluations have been made by UX novices, thus some aspects might have been missed or overlooked. Since we are still learning what makes a good user interface great, we will continue to improve our ideas and implementations of our UI going deeper into the semester.
