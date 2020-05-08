# Sprint Challenge: User Interface and Git

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied semantic HTML, CSS fundamentals, git, and responsive design. In your challenge this week, you will demonstrate proficiency by creating a fully responsive website that has some missing HTML elements as well as CSS specificity problems that need to be solved.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, git, and responsive design.

> You have **three hours** to complete this challenge. Plan your time accordingly.


## Introduction

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and make your page responsive for mobile. You will be working with a pre-existing web page, allowing you to get a taste of what it is like to inherit code from someone else, as will regularly happen on the job.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home page and mobile version. 

 [Click here for home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)
 
 [Click here for tablet example](design/tablet.png)


[Click here for mobile example](design/mobile.png)

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?
    They are HTML tags used to give meaning to your code. This way, any other person reading
    your code would have an easier time knowing what the various content between those
    tags are supposed to be on the web page.

2. What are the 4 areas of the box model?
    In order from furthest out to innermost:
    Margins -- These are spacing on the outside of the box. Can position box around layout
    Border -- The edge of the box itself. Can also have thickness and styles
    Padding -- The spacing inside the box, outside the content.
    Content -- The item itself being displayed (text, images, forms, etc)

3. While using flexbox, what axis does the following property work on: ```align-items: center```?
    "align-items" is the cross-axis of a flexbox. So if the flex-direction is row (default) or row-reverse, the align-items axis would be equivalent to the Y-axis on a Cartesian Plane. If flex-direction is column or column-reverse, then the align-items axis would be equivalent to th X-axis on the Cartesian Plane.
    Specifically, "align-items: center;" would center the item(s) along that axis.

4. Explain why git is valuable to a team of developers.
    Git allows multiple developers to work on the same project together, even if they're located across long distances and save various versions of the project from each developer.

5. Define mobile-first design in your own words.
    "Mobile-first" dictates an initial layout design for screen sizes found on mobile devices, but allows for modifications of the layout for users that might use devices with larger screen sizes (so the layout doesn't appear tiny) up to a desktop screen.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Instructions

### Task 1: Project Set Up

- [ ] Create a forked copy of this project
- [ ] Add your team lead as collaborator on Github
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!)
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly
- [ ] Push commits: git push origin `<firstName-lastName>`

### Task 2:  Minimum Viable Product

Your finished project must include all of the following requirements:

#### Home Page

[Review the provided design files](/design). Notice the navigation and header images are missing in the starter code.

* [ ] Build the HTML and CSS to create the missing navigation and header
* [ ] Link the `About` navigation item to an about.html page (you'll also need to create `about.html`)
* [ ] Make your design responsive such that it is accessible on mobile(500px) and tablet(800 px) and matches the [mobile](design/mobile.png) wireframe
*  Add responsive breakpoints to your code by using media queries

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [ ] box1: `teal`
* [ ] box2: `gold`
* [ ] box3: `cadetblue`
* [ ] box4: `coral`
* [ ] box5: `crimson`
* [ ] box6: `forestgreen`
* [ ] box7: `darkorchid`
* [ ] box8: `hotpink`
* [ ] box9: `indigo`
* [ ] box10: `dodgerblue`

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items.  Come up with content and images that fit the theme.  
* [ ] Introduce CSS animations to your site.
* [ ] Build a contact page and create a form with several inputs of your choosing

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master
