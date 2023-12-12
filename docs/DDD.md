# Detailed Design Document – Online Task Management System

## Author Info
- Name: [Mario-Martínez-Lozano]
- Course: [First-Engineering-Computer-Science]
- Group: [4-C]

## Description

This project is based on HTML/CSS/JS code, designed for the work of the Fundamentals of Computer Engineering subject, 
it tries to ensure that users can easily follow each section and section in an efficient manner. It is also designed 
for onion routing search engines such as Tor Browser, which allows us to view this page on the Internet without having 
to download it and view it locally if not remotely.

For more information contact [marichu.private@proton.me] with any additional questions or comments.

## 1. Introduction

### 1.1 System Objective
The system aims to provide an online platform for effective task and project management. 
It will allow users to create, assign and track tasks, as well as collaborate on projects efficiently.

## 2. System Architecture

### 2.1 Frontend

#### 2.1.1 Technologies Used
- JavaScript Framework: menu.js
- Style: CSS with Sass preprocessor

#### 2.1.2 Component Structure
- Home: Shows general information of the website.
- About: Shows a short description about Walter White. This section includes a short description based
         on a short description, a resume, two photographs, and some links to social media accounts.
- Contact: Includes a form for all users to contact me.
- Red: Show information about your partners' pages. This means that your partners' websites are linked.
- Topic: Shows information about a topic (Proxychains) chosen and developed with images and links.
- Fundamentals of Computer Engineering: Shows the course program, showing the different topics grouped together. 
  In addition, it includes a page to play games and another where you can find a link to access the onion version.

### 2.2 Backend

#### 2.2.1 Technologies Used
- Programming Language: menu.js
- HTML: developed with HyperText Markup



## Known Issues

1. Error 404 - Not Found:

Currently, the 404 page exist but does not do the function, there is a problem when trying to search for a page that does 
not exist, since there is no 404 page that directs you to the previous one. This is one of the most well-known errors and 
occurs when the server cannot find the requested page. It is commonly associated with web pages not found. We are working 
to resolve this issue in the next version.

2. Error 403 - Forbidden

Currently we do not have a 403 error page developed that tells us that this is the cause of the failure, this error 
indicates that the server understood the request, but refuses to authorize it. The user may not have the appropriate 
permissions to access the page or resource. We are working to resolve this issue in the next version.

3. Error 500 - Internal Server Error

Currently we do not have a 500 error page developed that tells us that this is the cause of the failure, this is a generic 
message that indicates a problem on the server. It may be due to a bug in the application code, problems with server 
configuration, or even server overload. We are working to resolve this issue in the next version.

## Conclusions and Next Steps

So far, the development of the system has progressed according to the initial plan. We have successfully implemented the basic functions requested for this project, we are open to receiving valuable feedback from users to improve. However, we recognize that there are still areas for improvement, especially in the errors that occur after searching for a non-existent page since the 404 error page is still in development and will appear in the next version.

## Next steps

1. **Release of Version 1.1:** We will address known issues and release a new version that improves the stability of the code in addition to suggestions from the community.

2. **Integration of New Features:** We are planning the integration of new features, such as the ability to add tags to tasks and message notification on the screen.

