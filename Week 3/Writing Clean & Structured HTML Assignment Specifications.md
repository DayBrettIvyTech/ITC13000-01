Activity Overview
In this activity, you will create a simple webpage while practicing professional HTML coding standards. You will use block elements, text elements, character references, indentation, and comments to produce code that is neat, consistent, and easy to maintain.

Learning Objectives
After completing this activity, you should be able to:

Apply proper HTML coding standards.

Organize a webpage using block elements.

format and emphasize content using text elements.

Display reserved and special characters using character references.

Use indentation and comments to improve readability.

Validate and review an HTML document for errors.

Scenario
You have been asked to create an informational webpage for a college technology club. The page will introduce the club, describe its activities, provide a meeting reminder, and display copyright information.

Another developer may need to update the webpage later, so your HTML must be organized and easy to understand.

Part 1: Create the HTML Document or Use Your Current HTML Webpage
Create a folder named:

coding-standards-activity

Inside the folder, create a file named:

index.html

Add the basic HTML document structure:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Technology Club</title>
</head>
<body>

</body>
</html>
Part 2: Apply Coding Standards
Your document must follow these standards:

Use lowercase letters for all HTML tags and attributes.

Indent nested elements consistently using four spaces.

Include closing tags for all elements that require them.

Place each major element on its own line.

Use meaningful text and page sections.

Include comments identifying the major sections of the webpage.

Check your spelling and capitalization in the visible content.

Example comment:

<!-- Main page heading -->
Part 3: Add Block Elements
Inside the <body> element, add the following block elements:

One <h1> containing the club’s name.

One <h2> for an “About the Club” section.

One <p> describing the club.

One <h2> for an “Upcoming Activities” section.

A <div> containing information about at least two club activities.

One additional paragraph containing meeting information.

Example structure:

<!-- About section -->
<div>
    <h2>About the Club</h2>
    <p>The College Technology Club helps students develop technical skills.</p>
</div>
Remember that block elements normally begin on a new line and help create the structure of the page.

Part 4: Add Text Elements
Use each of the following inline text elements at least once:

<strong> to identify important information.

<em> to emphasize a word or phrase.

<span> to identify text that could be styled later.

Example:

<p>
    Our next meeting is on <strong>Thursday at 4:00 p.m.</strong>
    All students are <em>encouraged</em> to attend.
</p>
Your text elements must appear inside a block element such as a paragraph or <div>.

Part 5: Add Character References
Use the following character references somewhere on the webpage:

Common HTML character references and their suggested uses
Character reference	Displays	Suggested use
&copy;	©	Copyright notice
&lt;	<	Display an opening HTML bracket
&gt;	>	Display a closing HTML bracket
&amp;	&	Display an ampersand
Example:

<p>Web Design &amp; Development Club</p>
<p>HTML elements use symbols such as &lt; and &gt;.</p>
<p>&copy; 2026 College Technology Club</p>
Enter the actual character references in your HTML code. Do not replace them with the displayed symbols.

Part 6: Add Comments
Include at least four HTML comments. Use comments to identify these sections:

Page header

About section

Activities section

Footer

Example:

<!-- Activities section -->
Comments should explain the organization of the code without appearing on the webpage.

Required Page Content
Your completed webpage must contain:

A valid basic HTML structure

One <h1> element

At least two <h2> elements

At least three <p> elements

At least two <div> elements

One <strong> element

One <em> element

One <span> element

All four required character references

At least four helpful HTML comments

Consistent indentation

Properly closed elements

Lowercase HTML tags

Testing and Review
Open index.html in a web browser and confirm that:

The page title appears on the browser tab.

All headings and paragraphs are visible.

The copyright, angle brackets, and ampersand display correctly.

HTML comments do not appear on the webpage.

The code is neatly indented.

Every required element is present.

All elements are properly closed.

You may also check your document using the W3C Markup Validation Service.

Reflection Questions
Answer each question using two to three complete sentences.

Why is consistent indentation important when writing HTML?

What is the difference between a block element and a text or inline element?

Why must character references be used for certain symbols in HTML?

How can comments help another developer maintain a webpage?

Identify one error you found and corrected while reviewing your document.

Submission Requirements
Submit the following:

Your completed index.html file.

A screenshot of the webpage open in a browser.

Your answers to the five reflection questions.

Before submitting, make sure your name and the activity title appear in an HTML comment near the top of your file:

<!--
    Student: Your Name
    Activity: Writing Clean and Structured HTML
    Date: Month Day, Year
-->