# Web Debugging and Optimization Exercise

## Overview

This exercise is designed to improve your skills in web debugging and optimization. You will be working with an intentionally flawed web application. Your task is to identify and document the problems in the provided HTML, CSS, and JavaScript files.

## Instructions

Copy this README.md into your Devtools REPO in a new MD file called Day-5.md

### Step 1: Identify Problems

Go through the provided files (`index.html`, `style.css`, and `app.js`). Each file contains several marked problems (indicated by comments like `<!-- Problem 1: -->`, `/* Problem 5: */`, etc.). Your task is to identify what each problem is and why it is an issue.

### Step 2: Document Each Problem

In this README.md file, document each problem. Write a sentence for each problem explaining what the issue is and why it's problematic. Use the format below for your documentation:

#### Problem 1:

- Description: The meta and title tags are missing in the head.

#### Problem 2:

- Description: I don't think there's a problem but maybe change the alt attribute from "Large Image" to "placeholder image" or the size of the image.

#### Problem 3:

- Description: I think the use of the jquery script.

#### Problem 4:

- Description: A class attribute for inline-style doesn't exist. The style tag in the head is not needed.

#### Problem 5:

- Description: The use of !Important rule is unnecessary.

#### Problem 6:

- Description: It's using CSS selectors that don't exist.

#### Problem 7:

- Description: Its using a CSS selector - img#largeImage

#### Problem 8:

- Description: The CSS selector.

#### Problem 9:

- Description: [Your explanation here]

#### Problem 10:

- Description: The code doesn't really serve a purpose. Althought it's variable is used for problem 11.

#### Problem 11:

- Description: Instead of using jquery, javascript should be used instead.

### Step 3: Propose Solutions

For each identified problem, propose a solution or an optimization strategy. Briefly describe how you would fix the issue.

#### Problem 1:

- Solution: First I would run a Lighthouse audit. Add meta and title tags.

#### Problem 2:

- Solution: Run Lighthouse and network to see if the image has issues performance wise.

#### Problem 3:

- Solution: Remove the jquery script and use the app.js.

#### Problem 4:

- Solution: Delete the inline-style class from the head and either place in the CSS file or on the tag I want styled.

#### Problem 5:

- Solution: Remove it the !Important rule because it's not needed.

#### Problem 6:

- Solution: Remove

#### Problem 7:

- Solution: Remove the img from img#largeImage.

#### Problem 8:

- Solution: Use h2 alone as the selector or #profileContainer h2 without the > between.

#### Problem 9:

- Solution:

#### Problem 10:

- Solution: It didn't have any problems

#### Problem 11:

- Solution: use javascript instead.

### Step 4: Reflect

There are a lot things that I need to work on. I don't fully understand the jquery or problem 9. However, I found running the lighthouse audit to be helpful and pick up some errors and performance issues.
