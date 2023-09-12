Title: Herzbahnhof
Date: 2023-09-11
Slug: herzbahnhof
Summary: Creating a website to promote rural development 

**Creating a website to promote rural development** 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Last summer 2022 I joined a creative pop-up space in an old train station in the small rural town of Herzberg (Elster). I designed the website „Herzbahnhof“ for two reasons. First, provide detailed information to Herzberg's citzens and interested persons about the temporary creative space. Second, collect ideas from the website's visitors about how the old train station could be used in future.

![back button](/images/herzbhf.png "image of Herzbahnhof landing page")

**Roles:**

+ User Research 
+ UI Design
+ Web development

**Tools:**

+ Figma, Miro
+ Visual Studio Code
+ HTML, CSS, JavaScript

-----------

**Challenge:**
Qualitative interviewing of visitors in the pop-up space revealed a wealth of thoughts and ideas about the future of the train station. But how could more voices be heard and a higher quantitity of ideas be collected? 

**Solution:**
I decided to support the idea collection with an online form on a website of the building. An easy and straightforward way to let people contribute their ideas in a simple form placed in the center of the landing page. Finally, the collected data should inspire more elaborate concepts about the building's prospective utilisation.

----

**RESEARCH**

**Data collection and analysis:**

From the interviews, I extracted the participants' ideas and sorted them into clusters. The analysis revealed two main projections for the building's "identity", made up out of its historic retrospective and future continuation. 

![clusters](/images/miro.png "idea clusters past future")

These two main dimensions needed to be represented on the "Herzbahnhof" website. A navigation bar was created, with two menu items and respective page sections that would provide detailed information regarding the past and future of the train station. To draw users' attention to these notions, the navbar is kept simple with only these to menu items ("Geschichte" and "Perspektiven"). 

**Testing the navigation menu wording:**

Three test persons were asked for their preference regarding the nav items' wording. They rejected the term "future" for its absoluteness. Instead, the term was exchanged by the more open and flexible "Perspektiven", indicating the subjective nature of the ideas for the building's possible future.

Feedback on successful form input was required by all test users. A page was added which is now displayed on form submission.

![feedback page](/images/danke.png "danke für Ihre Idee!")

----

**UI DESIGN**

**Form elements:**

Apart from the navigation bar, the other central element on the landing page is the form. Placed below in the center between past and future below the navigation, it refers to the present time. I chose a yellow background, a signal colour, that it used on train station timetables to indicate departure times of trains. The font type is kept in a style similar to the proprietary DB type. 


**Logo:**

I created a logo to communicate the uniqueness of the building as reported in the interviews with the Herzberg inhabitants. It shows a heart and the German abbreviation "Bhf" for train station inside, which refers to a pun made up from the words Herzberg and Bahnhof "Herzbahnhof". 

![logo](/images/logo.png "herzbhf logo")

----

**DEVELOPMENT**

I implemented the website with Visual Studio Code and common web technologies (HTML, CSS, and JavaScript) while using as little client-side rendering as possible, for mindful energy use. I included a Google-Api for an online spreadsheet which serves as a database for user data inputted via the form.


-----
**TAKE AWAYS & LEARNINGS**

+ Designing for digitally enabled citizen participation implies expertise about the procedures and implementation of local politics. Questions were raised by Herzberg's inhabitants about the purpose of the idea collection regarding any impacts on the old train station as a public space. For these reasons, I decided not to deploy the website.
+ A focus on either UI/UX design, user research, technical development or on product management is recommended when creating digitial applications which may have a political impact.
