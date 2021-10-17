# Code Refactor Training Project

## Table of Contents

0. [Project Files](#project-files)
1. [Introduction](#Introduction)
2. [Project Description](#project-description)
3. [Technologies](#Technologies)
4. [Acknowledgements](#Acknowledgements)
5. [Questions](#Questions)

## Project Files
-  my GitHub repository: [Code-Refractor-BCS-Project-One](https://github.com/Composition7/Code-Refractor-BCS-Project-One)
-  [README.md link](https://composition7.github.io/Code-Refractor-BCS-Project-One/)
-  ![Andrew Leonard's Code Refractor Project Screenshot](./Develop/assets/images/Horiseon_SEO_Screenshot_A_Leonard_2021-10-17_14-59-07.png)

## Introduction

I'm Andrew Leonard, I'm a new developer, and this is my first assigned project for UCLA Extension's Coding Bootcamp.

## Project Description
Given a very messy .html and .css file, clean it up so it makes sense and can be improved upon

### Assessment Criteria 

#### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

#### Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
#### Criteria Breakdown
<table>
  <tr>
    <th>Criteria</th>
    <th>When I...</th>
    <th>Then I...</th>
    <th>Therefore...</th>
  </tr>
  <tr>
    <td>accessibility standards</td>
    <td>view source code</td>
    <td>find semantic HTML elements</td>
    <td>for sure use <code>article</code>, <code>header</code>, <code>footer</code>, <code>section</code>, and <code>nav</code>. Use <code>aside</code>, <code>main</code>, and others if need be.  </td>
  </tr>
  <tr>
    <td>HTML Structure</td>
    <td>view HTML elements</td>
    <td>see a logical structure independent of styling and positioning</td>
    <td>(re)arrange HTML in "top to bottom" fashion</td>
  </tr>
  <tr>
    <td>image elements</td>
    <td>view image elements</td>
    <td>see alt tags</td>
    <td>add alt tags to all images</td>
  </tr>
  <tr>
    <td>heading</td>
    <td>view heading attributes</td>
    <td>see sequential order</td>
    <td>rearrange heading attributes? Seems done to me.</td>
  </tr>
  <tr>
    <td>page title</td>
    <td>look at page title</td>
    <td>see a concise, descriptive title</td>
    <td>change page title</td>
  </tr>
</table>

#### Additional Criteria
<table>
    <tr>
        <th>Category</th>
        <th>Criteria Description</th>
        <th>Task</th>
    </tr>
    <tr>
        <td>Technical</td>
        <td>Links function</td>
        <td>fix links in <code>nav</code></td>
    </tr>
    <tr>
        <td>Technical</td>
        <td>CSS refactoring</td>
        <td>Go through CSS and simplify/update. This is the meat of the assignment</td>
    </tr>
    <tr>
        <td>Technical</td>
        <td>CSS comments</td>
        <td>add comments for readability</td>
    <tr>
        <td>Deployment</td>
        <td>live URL</td>
        <td>Put page up on Github Pages?</td>
    </tr>
    <tr>
        <td>Deployment</td>
        <td>No errors</td>
        <td>Test to make sure it loads?</td>
    </tr>
    <tr>
        <td>Deployment</td>
        <td>GitHub URL</td>
        <td>Include GitHub URL in this README.md</td>
    </tr>
    <tr>
        <td>Deployment</td>
        <td>GitHub repository contains application code</td>
        <td>If I include the GitHub repo, isn't that a given?</td>
    </tr>
    <tr>
        <td>Application Quality</td>
        <td>Screenshot</td>
        <td>Resembles provided screenshot</td>
    </tr>
    <tr>
        <td>Repo Quality</td>
        <td>Repo has unique name</td>
        <td>Rename repo</td>
    </tr>
    <tr>
        <td>Repo Quality</td>
        <td>file structure & naming conventions, easy to find files</td>
        <td>maintain standard file structure</td>
    </tr>
    <tr>
        <td>Repo Quality</td>
        <td>class/id naming, indentation, quality comments, etc. stay organized</td>
        <td>keep files organized, add comments to commits</td>
    </tr>
    <tr>
        <td>Repo Quality</td>
        <td colspan="2">README is descriptive, includes screenshot, and link to deployed application</td>
</table>

## Technologies

-   HTML
-   CSS
-   Git

### Technology Stumbles
I was unable to implement NPM with Prettier and StyleLint.

## Acknowledgements
Many thanks to my tutor, [Omar Carmona](https://www.linkedin.com/in/omar-c-88746b174/)!

## Important Questions
### GitHub Pages 
When I try to put my version of the .html on GitHub pages, it's showing my README.md url, not the site itself. How do I adjust that? 

### "Github repo contains application code
I believe I've done this, but it seems so obvious, I'm worried I'm misunderstanding this part of the assignment

### Semantic Elements
The `article` element example at [W3 Schools](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_article2) implies it's appropriate to nest articles inside articles. This is the semantic approach I used in my project.

## Non-Important future Questions
### Using NPM/Prettier/styleLint
I wasn't able to figure these out. Obviously these tools are overkill for this small project, but I can see the value when working on big sites with many people.


