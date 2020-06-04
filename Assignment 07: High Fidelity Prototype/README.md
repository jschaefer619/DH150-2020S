# Assignment 07: Hi-Fidelity Prototype

### By Jack Schaefer

## Summary and Purpose

The high fidelity prototype is an interactive tool used to develop then directly test new concepts, aesthetics, and organizational schemes. It is typically developed later in the design process, often conceived from the findings of prior testing, research, and heuristic evaluation.

This particular high fidelity prototype is a redesign of the existing UCLA Radio website. Decisive changes were made to the aesthetics of the webpage. The landing page was dramatically simplified to reduce noise and strengthen the presence and sensibilities of the UCLA Radio brand. There was a dramatic reorganization in the structure of the Show scheduling. Filters were implemented to organize content. More affordances were made for User-Dj interactivity. 

## Tasks

Based on the persona research, these three tasks were used to test this Prototype. A few minor additions and tweaks were made to the tasks - primarily to make the tasks comprehensible to testers.

Task One (Emma Persona): Imagine that you have recently taken interest in electronic music. Find a show that plays electronic music, and try to find a playlist associated with that show.

Task Two (Chuck Persona): A close friend has joined UCLA Radio, and you are very proud of them!! Try to find their showtime for their show. You know their DJ name, but not their show name. Also, find the donation portal to UCLA Radio.

Task Three (Lee Persona): You love DJ Lee’s radio show, Nostalgia Trip. You are currently tuned into her show, and you want to let her know you appreciate her tracks by leaving a comment! Leave a comment on her feed, and try to customize your username too.

## Graphical User Interface

Landing page:

<img width="1438" alt="landing screen" src="https://user-images.githubusercontent.com/56604738/83311591-85486e80-a1c4-11ea-9699-d44c2b4d9925.png">

Scrolling down...

![scroll down](https://user-images.githubusercontent.com/56604738/83311595-87123200-a1c4-11ea-9dcf-0b1086896a11.png)

Streaming interface and chat at bottom of screen:

![chat](https://user-images.githubusercontent.com/56604738/83336356-91d1d300-a267-11ea-8985-6fd249f72a63.png)

Schedule page (notice filters and new weekly sorting):
![schedule ](https://user-images.githubusercontent.com/56604738/83336305-2c7de200-a267-11ea-8756-f0f3c9f61ba9.png)

Image of show detail (new Spotify connectivity):

![show detail](https://user-images.githubusercontent.com/56604738/83336361-aa41ed80-a267-11ea-8188-af452bd1a6b1.png)

## Typography and color scheme

The avenir font (geometric san serif) was used for the majority of body text and sub-headings. Headings and some branding text was in the coolvetica (scratch build san serif) font. Coolvetica's feel meshed well with the branding, while avenir was more conventional and highly readable, while also pairing well with coolvetica.

The Figma plugin Contrast was utilized to test background text contrast.

| <img width="295" alt="dark pink : light pink" src="https://user-images.githubusercontent.com/56604738/83336798-402b4780-a26b-11ea-805f-61dbdc24bb4b.png">  |  <img width="296" alt="dark pink: white" src="https://user-images.githubusercontent.com/56604738/83336804-4b7e7300-a26b-11ea-972d-6170d877685a.png">
 | <img width="298" alt="dark pink : grey" src="https://user-images.githubusercontent.com/56604738/83336823-6fda4f80-a26b-11ea-99f3-c92c93aab456.png"> | <img width="295" alt="text over gradient" src="https://user-images.githubusercontent.com/56604738/83336850-af08a080-a26b-11ea-84c7-c37177b1885e.png">  | <img width="296" alt="text gradient pink:black" src="https://user-images.githubusercontent.com/56604738/83336854-b334be00-a26b-11ea-8c28-918a730b3ff4.png"> | <img width="301" alt="text gradient pink" src="https://user-images.githubusercontent.com/56604738/83336857-b760db80-a26b-11ea-8df7-ba29c0883276.png">|  

The color utilized, which include pink(FFA5E2), dark pink(2B1B26), black(000000), white (FFFFFF), and grey(E5E5E5) were paired for sufficient contrast with respect to readability. Pink has been traditionally used for UCLA Radio branding, and is exciting and eye-catching. The other colors were selected because they were comparatively neutral and could contrast effectively against the pink.

The background gradients used on the landing page, about page, and contact page did pose some small issues regarding contrast - though their contrast ratings were passable. In later iterations of this prototype, a new gradient may be utilized to improve this without detracting from the aesthetic - as the test users responded quite well to the gradient look.

## Wireframe
<img width="593" alt="wireframe" src="https://user-images.githubusercontent.com/56604738/83337621-07db3780-a272-11ea-8d40-bbe818283132.png">

The above wireframe is a bit incomprehensible from this view. Admittedly, I went a bit beyond the scope of the assignment by integrating text rollover features (through Figma's 'overlay' feature) to better communicate navigation points to test users. Many frames were used to properly implement the filters for shows and blog posts. Implementation of these features in the prototype was useful, but leads to some confusion from this view. I encourage those who would like a better understanding of the wireframe to directly interact with the prototype.

[Link to the Figma prototype player.](https://www.figma.com/proto/eGnl7poccbveGvFoznV3Wc/High-Fidelity-Prototype?node-id=1%3A2&viewport=318%2C274%2C0.07959148287773132&scaling=min-zoom)
[Link to the Figma editor.](https://www.figma.com/file/eGnl7poccbveGvFoznV3Wc/High-Fidelity-Prototype?node-id=0%3A1)

## Impression Test & Cognitive Walkthrough

[Link to a video of Impression Test and Cognitive Walkthrough of all three tasks.](https://drive.google.com/file/d/1yY47fLSWISYoOnJTtQZVHb6OGMjVZn6d/view?usp=sharing)

The impression test was largely positive. Users were quite receptive to the use of imagery on the landing page to capture the attention of the user. The colors were bold, but also well received. The large text on the navigation bar eased use.

Similarly, the cognitive walkthrough was successful. Our user was able to effectively navigate the webpage with little to no unwanted or unnecessary interactions. Initially, our tester was unsure where a playlist might be located, but quickly found it by navigating to the 'show details' page. The tester did recommend making the show images clickable, rather than only the nearby text associated with the show name. This feedback was appreciated, and clickable show images were implemented into later versions of the prototype.

## Summary

The high fidelity prototype tested very positively with users. The shift to a modernized, image-supplemented design greatly improved the aesthetics of the UCLA Radio website. Navigation was intuitive and interconnected, most core pages were able to directly navigate between each other through sensible linking text.

Should I continuing iterating upon this prototype, I would consider changing some of the gradients for better contrast with text. I believe that some of the headings could be modified to better suit user needs - perhaps 'music' deserves its own heading, and would contain more information on DJ playlist and music recommendations of the radio station.

Reflecting on my experience with Figma, I realize that I did not utilize the full functionality of the 'component' system in Figma until later in the prototype, which lead to a bit of redundant editing of the prototype early on. Furthermore, I did go a bit beyond the scope of this prototype assignment, which lead to some unnecessary challenges in the design process. But I do not regret the extra time invested into developing this prototype, as this further developed my experience with the many features of the Figma prototyping tool. I anticipate I will use Figma in the future.
