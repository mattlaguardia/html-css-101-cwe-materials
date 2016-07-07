---
title: Coding 101
duration: "2:00"
creator:
    name: Melody Serra
    city: San Francisco
---

> #### *Guiding Questions When Using This Template*
>
> - [ ] Are the learning objectives measurable?
>   - [ ] Are there between 2-5 learning objectives?*
>   - [ ] Are the learning objectives specific enough?
>   - [ ] Do these learning objectives help students work toward the unit project?
>
>
> - [ ] How will this lesson culminate? (final activity + conclusion; should be 15-25 mins)
>
>
> - [ ] Are activities spaced out with enough time for each?
>   - [ ] Did you include knowledge "Checks" or activities at the end of every component to test comprehension?
>   - [ ] If reusing an existing resource, is there enough content for a given length of time?
>
>
> - [ ] Did you provide guidance for both students & instructors?
>   - [ ] What will instructors have to do to prepare for this lesson?
>   - [ ] What will students have to do to prepare for this lesson?
>   - [ ] What should students do to review or prepare for the next lesson?
>
> #### *How to Use This Template*
> * Static Components: Reserve roughly 5 min for Opening, 5 unscheduled "buffer" mins for overrun, & at least 5 min for Conclusion (end of lesson review).
>
>
> * Modular Components: The units of instruction are: Intro, Demo, Guided-Practice, & Independent-Practice. These can be cycled or intermixed in various orders, depending on the topic / content.

> #### *Components of the lesson plan*

> - Opening: this only happens once; used to introduce the agenda, review material, and provide a motivating example / the problem we're trying to solve with this skill/content
> - Introduction: this is a section dedicated to introducing and contextualizing new vocabulary, ideas, and code syntax that will be practiced in later sections
> - Demo: an instructor-led session demonstrating proper techniques or syntax examples
> - Guided Practice: interactive instructor by which the instructor engages with and probes students for answers to guide the discussion or activity
> - Independent Practice: a block of time where students are able to practice what they've learned; the instructor provides directions and the students use the directions to complete an exercise
> - Conclusion: a time to sum up the lesson, review the answers to a final independent practice, and/or pose discussion questions
> - Check: a moment to check to understand students are following; it can be done with a question about content, a general "How comfortable are you with this?", or the instructor can check the output of students code to ensure they've completed the assignment properly

> NOTE: the lesson you create does not have to follow a progression of Introduction > Demo > Guided Practice > Independent Practice - a combination of these is often ideal - but a lesson must always begin with an Opening and end wth a Conclusion.



---
# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Coding 101 : HTML + CSS


### LEARNING OBJECTIVES
*After this lesson, you will be able to:*

- Experience a typical GA learning experience through active learning exercises.
- Gain an introductory understanding of a new skill or insight that can be utilized in a professional setting.  
- Learn from materials created in conjunction with an experienced web-developer.
- Describe the difference between front-end and back-end code and the basic components of HTML, CSS, and Javascript.
- Use HTML and CSS to mark up a basic webpage. 

### STUDENT PRE-WORK
*Before this lesson, you should:*

- Install ____ editor on your computer.
- Have Google Chrome on your computer.

### INSTRUCTOR PREP
*Before this lesson, instructors will need to:*

- Have students install either Sublime Text 3 or Atom on to computer (choose one before telling students which one to install).
- Write learning objectives on board.
- Make sure wifi network and password  (GA Guest, yellowpencil)  is written on board, since students will need to be online to use codepen.io.

---
<a name="opening"></a>
## Opening (7 mins)

- Review current lesson objectives.
- Ask each student to share first name and answer the following question: "What brought you here tonight?."
- Include Hook / Real-world Relevance (why the content from this lesson is useful or important).

> Instructor Note: Use instructor notes to talk directly to instructors. Otherwise, write out lesson directions and materials in a student-facing voice.


***

<a name="introduction"></a>
## Introduction: (20 mins)

> Instructor Note: Discuss topic and explain by dividing parts into sections. Ask students to define, explain, or recall any **specific** elements relating to the current topic, when applicable.

#### How the World Wide Web Works:

In this section you will be discussing how the world wide web works. It is important here to include the following:

- When you type in google.com in to the browser, you are sending what is called a *get request*.
- The request is first received by the DNS (Domain Name System) server, which serves like the "yellow pages" - it finds which IP (Internet Protocol) address matches the domain name the user typed in.
- Once the corresponding IP address is found, the request continues to the web server, which hosts the files that make up the front end of a site.
- Tie this in to why we as front end developers are a vital part of this cycle.
- Have students turn to person next to them and explain this cycle in their own words as if they were explaining it to someone who is 12 years of age. 

#### What is Web Development?:

In this section you will be discussing what web development is on a high level. 

#### Web Production Workflow:

In this section you will be discussing the process of going from an idea to a fully developed and launched site. It is important here to include the following:

- UX - user experience, UX designers try to make it as easy as possible for people to use a webpage while achieving the purpose of the webpage.
- Design - take the wireframes created by the UX team and make them pretty (think about color palettes, font families...).
- Front End - bring the designs to life with HTML, CSS, and JS.
- Back End - gives the website a "memory," you can briefly touch on databases, authenticating users etc. 

#### Front End vs Back End in More Detail: 

- Describe in more detail how the front end differentiates from the back end. 
- Use the diagrams to help aid you with this description. 
- If time permits you can visit expedia.com and describe to students which part of the site is front end and which is back end. 

**Check:** Insert 1-2 guiding questions to ensure students are comprehending the material.

## Front End Languages: (7 mins)

- In this section you will break down for students that the THREE front end languages are HTML, CSS, and JavaScript. 
- You can use the terminology in the slides: 
	- HTML = bones
	- CSS = skin
	- JavaScript = brain
- You can also introduce the following:
	- HTML = noun (responsible for the 'things' on the page, e.g image vs paragraph)
	- CSS = adjective (responsible for styles like color or font family)
	- JavaScript = verb (responsible for behaviors, like drop-down menus)
- End this section with the ACTIVITY: DISTINGUISH BETWEEN HTML, CSS, AND JS. 

## HTML Syntax (5 mins)

- In this section you will explain the HTML syntax. 
- Start by explaining content tags, how they work, and what they are on a high level.
- You will then transition in to the demo.  

## Demo: HTML (20 mins)

You will be walking students through how to write the following tags in Code Pen:

	- h1 > h6
	- p
	- br
	- il/li
	- ol/li
	- img
	- a

- This is your opportunity to grab the attention of students and get them excited about code. Encourage students to show their neighbor what their site is looking like so far, etc. 
- If you would like you can have students practice searching img and a tags on their own and implement them in Code Pen. A recommended search I like to tell student's about is "img tag mdn." MDN is a resource I highly recommend. 

## HTML Scaffold (15 mins) 

In this section you will be explaining the HTML scaffold below to students. You will explain in detail what each line of code is responsible for. Some important things to mention:

- <!DOCTYPE html> tells the browser that you are using HTML5. 
- The html tag opens the HTML document, and the closing tag ends the HTML document. 
- Nested within the html tags are two sections, the head and the body. Just like with the human anatomy, the head is above the body. 
- The head contains information that you don't want the user to see within the browser window. 
- The title tags declares what will be shown in the tab. 
- The meta charset tag is responsible for character encoding. 
- The body contains everything you do want the user to see within the browser window. 

***

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Example</title>
    <meta charset="UTF-8">
  </head>
  <body>
    <h1>Example Page</h1>
    <p>This is an example page.</p>
  </body>
</html>
```

***

- Ask students to watch you as you create an HTML document. Take them through the workflow:
	- Create a folder
	- Open the entire folder in editor
	- Save a file in the editor as index.html in the folder created
	- Type out the HTML scaffold
	- Show students how to open the HTML file in the browser

<a name="ind-practice"></a>
## Independent Practice: Creating your first HTML file (15 mins)
Use the lesson topic/skill to create a deliverable that meets certain criteria.

> Instructor Note: This can be a pair programming activity or done independently.

Here is the prompt for the deliverable:

1. Create a folder on your desktop and title it “Coding 101” 
2. Open up the folder you just made in your text editor 
3. Save your file as “index.html” 
4. Type out the HTML basic layout  
5. Open up the HTML file in Google Chrome 
6. Add more content tags: h1-h6, p, ul/li, button, a, img to create an “About Me” webpage 
7. Keep your editor open

**Check:** Were students able to create the desired deliverable(s)? Did it meet all necessary requirements / constraints?

***

## CSS Syntax (10 mins)

In this section you will be going over the CSS syntax. Important concepts to include are:

- Start by explaining how the syntax differs from HTML.
- You will then transition in to the demo which will include showing students how to connect the HTML file to the external CSS file. 


<a name="demo"></a>
## Demo: CSS (5 mins)

Add styling to the basic HTML page you created in your last demo. Remember to connect your two files during your demo. Take them through the workflow:

- If closed, open up your folder than contains your HTML file in the editor 
- Save a new file in the editor as style.css (make sure it is saved in the same folder as the HTML file)
- Style at least one element 
- Save your file and open up project in the browser
- Ask students why nothing happened
- Students should respond that you need to connect the two files, once they do add a link tag to the head of your HTML file
- Refresh the page


```css
h1 {
  color: #85c9a9;
}
```

**Check:** By this point, students should be able to write out an HTML file from scratch so that they can now add CSS to their pages.



<a name="ind-practice"></a>
## Independent Practice: Topic (10 mins)
Use the lesson topic/skill to create a deliverable that meets certain criteria.

> Instructor Note: This can be a pair programming activity or done independently.

Here is a prompt for the deliverable: 

1. You should still have the “Coding 101” folder open in your editor
2. Create a new file from the editor, save the file as “style.css” 
3. Add a few CSS properties(color, background-color, font-family, text-align) to the content created in the last activity   
4. Connect your external CSS file to your HTML file 
5. Open up the HTML file in Google Chrome 

**Check:** Were students able to create the desired deliverable(s)? Did it meet all necessary requirements / constraints?

***

<a name="conclusion"></a>
## Conclusion (6 mins)
- Review independent practice deliverable(s). 
- If time permits you can go over the last slides which have to do with how to edit an existing webpage, and a discussion on who needs to know the content covered in this class, and what students can do after class. 
- Recap topic(s) covered in today's lesson.
- Cover homework and/or upcoming tasks.

***

### BEFORE NEXT CLASS
|   |   |
|---|---|
| **HOMEWORK** | Dash Project 1  |


### ADDITIONAL RESOURCES
- Add your own resources.
- There are a few listed in the slides, but feel free to remove these slides, change them, or just tell students that they are there for their reference.
