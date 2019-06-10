# FinityOne Backend Engineer Take-Home Project

  # Introduction

  At FinityOne, we prioritize functionality of data, speed of data, and security of data (in that order). This is a take home project that
  focuses on building/testing skills with Node.js backend. The primary objective of this is to get an understanding of the candidates aptitude
  to learn, adapt, and deliver code that works. Obviously, there are many optimizations that are possible, but getting the core delivered is
  the essence of the business at FinityOne. We hope to see the deliverance of the candidate through this project.

  DEADLINE: June 16, 2019 @ 12 PM MIDNIGHT. (Note: You don't have to finish everything, but do your best!)

  # Instructions

  The objective of this take home project is to build a simple backend to send, store, update, and delete emails. This is an email service utilized by
  a small business (5-10 employees), who need to send, update, and monitor emails in their inbox.

  The stages of the take home project are in order of difficulty, so if you feel something is easier, please try doing this IN ORDER. For example,
  the first task stage is the easiest, while the last task stage is the hardest.

  Clone the repository, `cd server && npm install`, and begin by coding within. To run the server, run `npm start` within the server folder.

  NOTE: You need to install Node before starting developing on the project.

  As a helper, you have 1 lifeline to get help from Heran (heran@finityone.com). Send an email to setup a Google Hangouts call to go over the lifeline.

  SUBMISSION: Email a zipped folder of your entire cloned repository with your work to heran@finityone.com

## STAGE #1

  FILE TO MODIFY: /server/api/email/emailController

  Create an endpoint to take in the following fields and return them back to the requestor:
    1) To email address (the email to which they are sending the email)
    2) Subject (the subject line of the email)
    3) Message (the main message of the email)
    4) Email Date (the date of the email being sent)
  Send the appropriate success/fail response.


## STAGE #2

  FILE TO MODIFY: /server/api/email/emailController

  Create another endpoint to take store the email into a database (with the same fields as STAGE #1) into a database (MySQL).
  Send the appropriate success/fail response.

  Note: You will need to install a database, develop a database connection, install the npm mysql module, and then import it into the controller.

## STAGE #3

  FILE TO MODIFY: /server/api/email/emailController

  Create another endpoint to update the sent email information. The following fields will be passed into the request:
    1) Subject
    2) Message
  Send the appropriate success/fail response.

## STAGE #4

  FILE TO MODIFY: /server/api/email/emailController

  Create another endpoint to grab all emails from the database, and send them in an array back as a response.


## STAGE #5

  FILE TO MODIFY: /server/documentation/index.js
  NO CODING NEEDED! Please write on: (no limit)
    1) What was the hardest part of the project?
    2) If you had to think of optimizations, how would you make the data faster in the database?
    3) If you could change one thing about this test, what would it be?
