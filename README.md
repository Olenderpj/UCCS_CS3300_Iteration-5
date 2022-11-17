# UCCS - CS 3300 Iteration 5

##  Description:
In this assignment, you are going to continue working on your individual portfolio software project. Using the wireframe 
sketches that you created earlier in the semester, you will start implementing your ideas and creating the HTML and Css 
web pages to display to users that look at your portfolio. <br>

This is your opportunity to exercise creative freedom and design your portfolio application in any manner that you see 
fit. Have fun with this iteration, learn something and implement something cool.

### Important  Note:
If you change the way that you design the front-end of your website, please resubmit an updated wireframe diagram to go alongside your changes <br>

**Purpose:** Learn how to use wireframe design documents to create HTML & CSS based web-applications.<br>
**Effort:** Individual <br>
**Time Estimate:** 3-6 hours based on experience.<br>
**Points:** <br>
**Deliverables:** .DOCX, .PDF, and other text-based document formats.

```diff 
- No compressed (.zip, .tar, etc.) will be accepted, make sure that all deliverables
- are all in one submission file.

 ```

---

## Expected Deliverables:
**[ 15 Points ]:** Link to your GitHub Repository containing all updated and working code.<br>
**[ 3  Points ]:** start image <br>
**[ 3  Points ]:** wireframe <br>
**[ 10 Points ]:** completed code <br>

**[ 3  Points ]:** start image <br>
**[ 3  Points ]:** wireframe <br>
**[ 10 Points ]:** completed code <br>

**[ X  Points ]:** References <br>
**[ 10 Points ]:** Paragraph write up of what you learned <br>

## Extra Credit Opportunity:
**If you attempt the extra credit, please make a specific heading for it in your submission document.** <br>
**[ X points ]:** Implement a minimum of 4 new unit tests and provide the associated code for each test in your submission.

---

## Instructions:

1. Ensure that the devise user views exist, under `app/views/users` you should see some additional directories associated with devise.
   1. If you don't see these directories, run the following command to generate them.
      - `rails generate devise:views users`

2. Add the following code to your projects controller
   ```ruby
         before_action :set_project, only: %i[ show edit update destroy ]
         before_action :authenticate_user!, only: %i[ new edit create destroy ]      
   ```
   
3. in the rails helper, 


2. You will now be modifying the following 3 views to look like the wireframe diagrams that you created in iteration 02 earlier in the semester. <br>
   1. Project "Show" View <br>
      - <br> 
   2. Devise Login Page <br>
      -  <br>
   3. Devise Registration Page <br>
      - <br>

```diff
+ Remember to push your code to GitHub early and often so that you avoid losing completed work.
```
**Repeat the following steps for each view that is modified**

1. Take a screenshot of the initial view to show your starting point.

2. Modify the HTML and CSS code for each of the views and push your code to GitHub when complete.<br>

3. Take a second screenshot of your finalized view to show your progress.


# Response Questions & Deliverables: 
1. Provide a screenshot of the following for all 3 of the views that you made changes to (Should be 9 total screenshots):
   1. Your wireframe diagram for each view (you created this in iteration 02.)
   2. What the view looks like before you make changes.
   3. What the view looks like after your changes have been made.


2. Provide a <ins> **small**</ins> portion of your HTML Code and give an explanation of what HTML tags you used, and how you
      structured your code.


3. Provide a <ins> **small**</ins> portion of your CSS Code and give an explanation of what the styling accomplishes.


4. Provide a **minimum** of **3** references that helped you learn something or solve a problem.

3. Write a 1 paragraph response for **one** of the following prompts: <br>
   1. What problems did you have and what process did you go through to solve them, and did you end up meeting your personal
      and assignment goals? <br>
   2. What's the one thing that you have seen in your classmates' work or process that you would like to try in
      your next iteration or project? <br>
   3. How has your previous experience (either school or professional) helped you accomplish your goals in this project? <br>
