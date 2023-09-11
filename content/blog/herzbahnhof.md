Title: Herzbahnhof
Date: 2023-09-10
Slug: herzbahnhof
Summary: Creating a website to promote rural development 

**Creating a website to promote rural development** 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Last summer 2022 I joined a creative pop-up space in the small rural town of Herzberg (Elster) which had been established for reutilisation purposes of an old train station. I designed the website of „Herzbahnhof“ for two reasons:
First, provide detailed information to Herzberg's citzens about the temporary creative space.
Second, collect ideas from the website's visitors about how the old train station could be used in future.

![back button](/images/herzbahnhof3.png "image of Herzbahnhof landing page")

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

From the interviews, I extracted the participants' main ideas and sorted them into clusters, showing two main projections for the building's "identity", made up out of its historic retrospective and future continuation. 

![clusters](/images/miro1.png "idea clusters past future")

These two main dimensions needed to be represented on the website. Therefore, the navigation bar has two menu items that respectively provide information regarding the past and future of the train station. To draw the users' attention to these main dimensions, the navbar is kept simple with only these to items ("Geschichte" and "Perspektiven"). 

**Testing the navigation menu wording:**

Three test persons were asked to articulate their preference regarding the nav items wording. As a main finding the users rejected the term "future" for its absolute connotation. Instead, it was exchanged by the more open term "Perspektiven", conveying the subjective nature of the ideas for the building's possible future.

----

**UI DESIGN**

**Form elements:**

Apart from the navigation bar, the other central element on the landing page is the idea posting form. Placed below in the center between past and future below the navigation, it can be recognised as the present dimension. I chose a yellow background, a signal colour, that it used on train station timetables to indicate departure times of trains. The font is in a style similar to the proprietary DB type. 

**Logo:**

I created a logo to communicate the uniqueness of the building as reported in the interviews with the Herzberg inhabitants. It shows a heart and the German abbreviation for train station inside, which refers to a pun made up from the words Herzberg and Bahnhof "Herzbahnhof". 

![logo](/images/logo1.png "herzbhf logo")

----

**DEVELOPMENT**

I've implemented the website using Visual Studio Code and the common web technologies, using as little client-side rendering as possible, for mindful energy use. For the input data via the form, a Google-Api was used and an online spreadsheet serves as a database for the user data.
