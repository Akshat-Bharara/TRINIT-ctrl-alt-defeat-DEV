# TRINIT-ctrl-alt-defeat-DEV

DEV03 - Test Formatter : A site where anyone can upload a pdf of question paper of quizzes and get an online mock for the same question paper. 


### Deployed link: https://trinit-8be36.web.app/

### Basic video demo: https://drive.google.com/file/d/15p63P-F6fwKmx65y7zTLWKAvPBrb5iQG/view?usp=sharing


## To access app 
- Login using gmail


## Technologies Used
- React
- Firebase

## List of Implemented Features

### Login and Registration: 

- User login/logout and User Registration using Firebase: Implemented using the Firebase Authentication API. The app handles API responses related to incorrect passwords, invalid emails, weak passwords etc.
- Implemented Auto-Login: The user doesn't need to authenticate everytime the website is restarted. Their authentication state is checked and they are redirected to the Home page if already logged in. 

### User Home Page:
- Test Collection Section that has 2 tabs - All and Personal.
- In All tab, all the global tests can be viewed and the test can be taken on clicking on Start test.
- In the personal tab, the user can create a new test by clicking on the Create New button.
- At last, there is a logout button to go back to the sign in page. 

### Creating Tests
- Test Generator: Users can upload a PDF/Image and get an online mock
assessment(text only) of the same with an option to upload an image for
each question.
- Answer Key: Users can fill in the answers of each question once the questions are generated from the pdf.
-  Tool: Users can directly make a manual online assessment(text and
image) without needing a PDF.
- Wider support: Support for different formats not limited to just JEE exam. The pdf scanning works for many types of pdfs. The only contition is that the questions should be of the format [ 1. 2. ] and the options should be of the format [ a) b) c) d) ].



### List of Planned Features
- Personal Space: Users can add friends and form groups with them.
- Ratings: Allow people to upvote a public test to distinguish between the
good and bad tests uploaded.


###
-Resource: Tool to perform Optical Character Recognition(OCR) with API
https://ocr.space.
