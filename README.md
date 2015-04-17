>#GSoC 2015 Proposal
>Organization: Fossasia

###1. Name and Contact Info

Name: Manoj Pandey
Email: manojpandey1996@gmail.com
Contact No: +919910089606
Website: http://manojpandey.co.nr
Blog:  https://namespacestd.wordpress.com/
Github: http://github.com/manojpandey
IM service and username: Skype, Username: manojpandey1996
Location (State, Country): New Delhi, India
Time Zone: Indian Standard Time(IST) or [UTC +05:30]

###2. Title and Aim of the Project
	"Social Media Wall"
This project will result in a web application to display social media posts and analytics with specified hashtag from various social media platforms using their API's and create a space where we can display content shared by the users with particular hashtag. The space will display archives from various social media platforms as long as reader is interested to read them. Initially the objective will be limited to the social websites Facebook and Twitter using Facebook and Twitter API respectively. The extended part of the project will be to get images from other platforms like instagram where we could get images with hashtags and merge them into the created utility, and finally make a mobile app (Android, iOS) out of it. 

###3. Synopsis
 First of all I'll create a basic template using HTML5/CSS3. I want the app to be available for mobiles too and going for a native app is time consuming as well as resource taking. We can develop the whole app using HTML/CSS, design it with AngularJS and finally using a small, yet powerful HTML5 framework: “Ionic”, that uses Cordova, and get the mobile app out of it easily. Fortunately Cordova comes up with a lot of useful plugins which can be used on the mobile app. The backend part will be implemented in Django using django REST framework. Initially, the plan will be to fetch the media from Facebook and Twitter using their API's and create the web app with it. For the mobile app we can generate our own API using django REST framework which can be then used for the mobile app. Developing the mobile app will come after making the web app. The UI of the app will be minimal and responsive providing a good user experience with the application.

###4. Benefits to the community
This app can be used to organise hashtag campaigns and do hashtag marketing. Also the community can incentivize attendees in a particular event and using particular hashtag to share their experiences.  
One can design a campaign or photo contest around a unique hashtag and let the community spread the word all over the social web. It can be used as the next-generation social wall events or venue! It can also be used to connect the audience with what's currently going on in social media by various organizations and companies for their own product.

###5. Deliverable and Timeline
The following table shows the schedule of this project. And progress will be visible on my GitHub repository here and I will write at least a blog post on my blog here to share the things I've done, problems I've met and how I managed to finish them, and some other experiences during the project.
Although there might be slightly changes of the schedule according to the project details or/and the advice my mentor will be giving to me, I am still confident that I can finish the project on time with reliable codes.  
The third column shows how the project dates/timelines are associated with GSoC Timeline and when will the milestones be reached. Important time periods or beginning of the time period is in bold.  Milestones and check points (i.e. the milestone deadlines) are also listed.

>Present - April 26
Researching on the project idea. Checking the possibility of integrating with other social media.
 **Community Bonding Period soon**
 
---

>April 27 - May 3
Getting familiar with assigned mentor(s) and discuss the questions I might have so far. Discussions about the project details and meeting dates with mentor(s).d
**Community Bonding Period**

--- 
>May 4 - May 10
More discussions about details of the project, make changes of project plans if needed.
Brush up existing skills needed for the project.
 Milestone 1 in progress
**Community Bonding Period**

---
>**May 11 - May 17**
Setting up the whole environment. Making changes to the coding timeline, if any after discussing with the mentor
Milestone 1 in progress 
**Community Bonding Period**

---
>**May 17 - May 24**
Making the initial version of the app with the decided structure and schema in Django.
 Milestone 1 in progress 
**Community Boding Period ends**

---
>**May 25 - May 31**
Discuss the API structure of the application  and the implementation of the progress with mentor.
**Work officially begins**

--- 
>**June 1 - June 7**
Testing the initial app with the feature of getting media from a hashtag.
 Milestone 1 in progress
**Work Period**

---
>**June 8 - June 14**
Work on the design part of the application and test the application made so far with
discussion on progress with mentor.
 Milestone 1 check point
**Work Period**

---
>**June 15 - June 21**
Extracting the content for the website using django rest framework and python-social-auth
 Milestone 2 in progress
**Work Period**

---
>**June 22 - June 28**
Preparing for the mid-term report. Discuss with mento(s). Document on changes made and do code style checking on the codes done so far. 
Milestone 2 check point
**Work Period & Mid-term report**

---
>**June 29 - July 5**
Adding Asynchronous JS calls for providing the ability to fecth media as long as the user is intended 
 Milestone 3 in progress
**Work Period**

---
>**June 30 - July 6**
Testing all of the implementations of the project. Discuss progress with mentor.
Milestone 3 check point
**Work Period**

---
>**July 6 - July 12**
Providing ability to moderate the content being displayed on the wall. Filtering the content on specific basis.
Milestone 4 in progress
**Work Period**

---
>**July 13 - July 19**
Testing all of the implementations of the project. Discuss progress with mentor.
Milestone 4 check point
**Work Period**

---
>**July 20 - July 26**
Generating the mobile app with the API endpoints using Ionic framework.
 Milestone 5 in progress
**Work period**

---
>**July 27 - August 2**
Fixing problems with code styles and testing all of the implements of this project. Start documentation. Discuss progress with mentor.
Milestone 5 check point
**Work period**

---
>**August 3 - August 9**
Documentation and preparing for the final report. Finishing unfinished parts, final checks on codes and documentation.
 Milestone 6 and 7 in progress 
**Suggested Pencils Down date**

---
>**August 10 - August 16**
 This time period is reserved in case of any unexpected issues. Discuss progress with mentor.
Milestone 6 and 7 check point 
**Firm Pencils Down date**

---
>**August 17 – August 24**
Finalizing GsoC 2015
**Student Coding Period Ends**

---



#### Milestones
I have broken the entire project task into small tasks which is necessary for me to get my time and everything else under control and organized, so that I can finish the tasks on time. So here are the milestones for the project and I will finish them one by one or as by discussing with the assigned mentor.

1.  Deciding Django Models structure and schema, design a minimal app to create hashtag campaigns
2.  Integrate Django web app with python-social-auth and Django REST framework. 
3.  Writing API end points, connecting API’s with asynchronous JS Calls that would dynamically generate content on walls. 
4.  Improving Django Web app and API end points to reduce unwanted content, i.e moderation.
5. Integrating Ionic Mobile App with API’s 
6.  Final testing of the app, both on web and mobile, testing for responsiveness etc.
7. ­ Documentation and detailing of the code.


###6. Biographical Info
I am currently a Computer Science undergraduate, graduating prospectively in 2018. I have been programming since 2 years fluently with C/C++, particularly for Competitive Programming. I started Python 6 months back and feel comfortable with HTML5, CSS3, JavaScript and AngularJS 
 I shall be able to devote my full attention and time to the project and can easily work on the project for around 35-40 hours per week. However, I am ready to put in any extra time and effort that might be demanded by the project. As far as I can as I can anticipate, I shall be having my vacations during most part of GSoC. However, my college does open towards the end of GSoC, in August. I shall not be having any exams during this period and I do not have any travelling plans as of yet.
I will maintain the resulting app and plan to contribute to it for a longer term after Google Summer of Code 2015.
My resume is attached here.