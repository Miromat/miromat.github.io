---
layout: page
title: Project Idea
permalink: /Project Idea/
weight: 5
---

# **Project Idea**

<img src="https://raw.githubusercontent.com/Miromat/miromat.github.io/master/assets/bvb.jpg" width="870">

#### **BVB News Feeder**
A personalised news mailer


##### **Overview**

My project idea is a personalised news feeder/mailer. Something like a website or application that searches for any news concerning a particular topic or keywords during the night to then present a summary to the user in the morning. In my case, this is going be BVB Dortmund, a football club from the German Bundesliga, that my son and I are following. That is the reason why I have branded it BVB Dortmund News Feeder, to give it a name.


##### **Motivation**

My main motivation is the lack of time I have got in the morning to read news, especially foreign sports news which update during the night. Working full time and studying full time leaves me with almost no spare time anymore to browse the Internet, to search all the different web sites and to check them for appropriate news, in my case football related articles. An application or website that could do that for me would be the ideal solution in my current situation. It is something I have not tried before and I feel like it would be the perfect project to work on and to complete by the time I finish my studies.


##### **Description**

Whereas other solutions offer general news summaries based on categories such as technology, politics, sports etc. from a predefined list of news websites, I would like to be able to specify even more details such the websites and more specific keywords than just a category. I am not aware of anything out there that is similar. This is more like a personal tool than something the mainstream Internet user would want or would use I believe.

My personal BVB version will probably have the below details hard-coded. However, the final product will feature an interface where the user will be able customise the following details:

The first test version will be a script or an application with the final product being a web-based interface.

Keywords:

* Enter a list of search keywords, categories
* Search for all of them separately or specify if two or more keywords have to match by entering them in the same line divided by a comma.

Websites:

*	Specify a list of websites you would like the program to search in
*	A possible extra option could be to have a ‘Search Google’ function to find additional articles in non-specified websites

Start Date:

*	This is the date that the bot will start searching from (calendar interface)

 Frequency:

*	The user will be able to choose how often an email is generated and sent.
*	Options will be: Daily, weekly, fortnightly and monthly

Filter:

*	This will allow the user to select/de-select languages, i.e. German, English, Italian, French
*	The filter will also allow the user to limit the number of articles sent by entering a mx value. Especially when an option such as ‘Search Google’ is selected, there may be the possibility of too many search results.

All settings will be saved after hitting the ‘save’ button. There will also be a ‘generate now’ button to test or generate an email straight away. This may take a bit of time depending on the number of websites and keywords entered though.

The email that the user will receive will contain hyperlinks to the articles with a title and possibly a one- or two-line description of the article.


##### **Tools and Technologies**

I should be able to realise this project with just open source and other free to use software.
I do have computers running macOS and Windows and would not need to purchase those.
This will be of advantage when testing the web application for compatibility with different browsers and operating systems. Overall the project should not cost me anything other than the electricity and Internet bills I am already paying.

Software:

*	Java, Java Script, HTML, maybe C++ (Eclipse IDE, Visual Studio)
*	PostgreSQL (free open source database to possibly store the search results)

Hardware:

*	Computers to develop the project. (already available)

Host:

*	The final web-based version of the application will require a host. (GitHub or another free host)


##### **Skills Required**

In order to successfully complete this project, only software skills are required. There is no need for a big development team or programmers who specialise in certain programming languages. I can see this being developed by a single person, in this case me, who will have to seriously work on his programming skills to get the project completed.

Break down of the different parts that need to be developed to make up the final product:

*	Website design to host the interface/web application (HTML, JS, CSS).
*	Bot/Robot development that searches and extracts the data from the news websites and stores it in the PostgreSQL database (not sure what language this will be in, I will need to do more research on that topic, possibly Java).


##### **Outcome**

If successful, this project will help me and possibly others managing their time more efficiently. As previously mentioned, I do not have the time anymore to search all the websites that I used to check quite frequently. Once this project is completed, I will be able to receive an email containing a list of news articles that I am interested in. There is no need to connect and to wait for websites to load, to then navigate and scroll through the websites to finally read the desired information. There is also the possibility of no new articles matching my interests. This will save me a lot of time that I can use to do other things. I will not get side-tracked by other news while browsing the websites. There is plenty of distraction that I would not be exposed to by ’just’ reading my email.
