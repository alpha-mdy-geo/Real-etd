<!DOCTYPE html>
<html>
<head>
</head>
<body>
A PROJECT REPORT ON

# Electronic Thesis and Dissertation

FOR

GMIT

SUBMITTED IN PARTIAL

FULFILLMENT OF INTERNSHIP

PROJECT

UNDER THE GUIDANCE OF

Director

Mr. Ravi Chhabra

Supervisor

Dr.Khaing Moe San

# SUBMITTED BY

    Ma Ei Mon Theint
    Ma Khaing Nyo Thein
    Ma Shwe Zin Oo
    Ma Nann Khaing Zar Thinn
    Ma Yun Me Me Thaw
    Ma Ei Cho Zin

University of Computer Studies (Mandalay)

Abstract

This project will present how to search thesis data and suggestions via online. Users can browse search button by author's name, year, title or degree and then the related answers will be received. Admin can insert up-to-date data, delete unnecessary data and update thesis data.

 For Front End, the project will be implemented by using HTML, Materializecss, Material Design Lite and JavaScript. For Back End, the system was implemented by using Real-Time Database of Firebase and JavaScript.

**ACKNOWLEDGEMENT**

 We would like to express our very great appreciation to our Rector U Kyaw Swar Soe , for his kind permission to send us internship Program. Then, we would like to express any special thanks to Dr. Daw** San San Tint , Pro-Rector, for her helpful recommendations and suggestions. And then our teacher Dr. Daw Khaing Moe San, Associate Professor ,** forher valuable and constructive suggestions during the planning and development of this project. They willingness to give their time so generously has been very much appreciated. Advice given by other academic lectures has been a great help in building the software solution.

       Also we obliged to staff members of University of Computer Studies (Mandalay) for the valuable information provided by them in their respective fields. We are grateful for their cooperation during the period of developing the system. Assistance provided infinity software development crew was greatly appreciated. Their contribution was worth a lot, in making this development a reality.

      Then also thanks to **Mr. Ravi Chhabra** , CEO of GMIT, for his trust to give us such a heavy responsibility project.

       We especially thanks to our parents and all our friends for providing encouragement and giving us a great support during internship programme.

**DECLARTATION**

We declare that this project report or part of it was not a copy of a document done by any organization, university any other institute or a previous student project group at University of Computer Studies (Mandalay) and was not copied from the Internet or other sources.

Project Details
Project Title 	Electronic Thesis and Dissertation System
Project ID 	Geo-Mandalar Investment & Technology Internship



List of Figures

Figure                                                                                            Page
Figure (2.1) Project Plan								21
Figure (3.1) Flowchart Diagram for ETDs					23
Figure (3.2) Use Case Diagram for ETDs					24
Figure (3.3) Sequence Diagram for ETDs					25
Figure (3.4) Home Page of ETDs							26
Figure (3.5) Admin Sign in Form                                                       27
Figure (3.6) Admin Choose Form							28
Figure (3.7) Create New Data Form						29
Figure (3.8) Browsing By Authors Form					30
Figure (3.9) Alert Box									31
Figure (3.10) Browsing By Title Form						32
Figure (3.11) Latest Form								33
Figure (3.12) Search By Year Form						34
Figure (3.13) Search By Year and Author Form				35
Figure (3.14) Search By Author Form						36
Figure (3.15) Search By Author and Year Form				37
Figure (3.16) Search By Degree Form						38
Figure (3.17) Search By Title Form						39
Figure (3.18) History Form								40
Figure (3.19) FAQ Form								41
Figure (3.20) Skill Form								42
Figure (3.21) Role and Profile Form						43
Figure (3.22) Contact Form								44

	
 
Chapter 1
Introduction

1.1	Introduction
                Nowadays, Mobile phones are very useful for everyone to communicate with each other. So, they are becoming an important part of our everyday life. Nowadays, reducing the men’s physical effort with the help of latest devices and technologies is on demand. The project provides us the complete and accurate information about thesis.
                The project named “Electronic Thesis and Dissertations System” is aimed to search easily thesis data. The project is developed for window side and mobile phones. Our project mainly focuses on basic operations like inserting new data, updating or deleting existing data, view thesis data and so on. This project has many advantages that to reduce users wait times, accessible from anywhere at any time and do not need storage space in libraries.
                  This project has the lists of titles, authors, year and degree on the website to find collections of thesis. Each collection has a short description to help users decide which one to use.
                   Our project is very useful for users who want to save their times, who can search easily data that users want to know and manual actions of the thesis for both users and admin.



1.2	Background of the System
 1.2.1 Evaluation of the literature relevant to the project area

         We have to consider about the method, approach, programming language and tools in developing the project. Methodology will be used as I structure the project plan; it will represent how the project will be processed. Thus we structure the project’s framework, we need to consider about the project development. In the project area, we can use HTML, Materializecss, Material Design Lite, JavaScript, Real-Time database of firebase and SAD. We must use UML technique to propose the business processes in the project area; we can define the process notations by using UML diagrams. In order to code the program, we can use many computer languages.

   1.2.2 HTML
     HTML is a computer language devised to allow website creation. These websites can then be viewed by anyone else connected to the Internet. It is relatively easy to learn, with the basics being accessible to most people in one sitting; and quite powerful in what it allows you to create.
              The definition of HTML is HyperText Markup Language.                                               
	HyperText is the method by which you move around on the web — by clicking on special text called hyperlinks which bring you to the next page. The fact that it is hyper just means it is not linear — i.e. you can go to any place on the Internet whenever you want by clicking on links — there is no set order to do things in.
	Markup is what HTML tags do to the text inside them. They mark it as a certain type of text (italicised text, for example).
	HTML is a Language, as it has code-words and syntax like any other language.


1.2.3	 Materializecss
                Materialize CSS is a UI component library which is created with CSS, JavaScript and HTML. It is created and designed by Google. Materialize CSS is also known as Material Design. It is a design language which combines the classic principles of successful design along with innovation and technology. Google's goal is to develop a system of design that allows for a unified user experience across all their products on any platform. It is used to construct attractive, consistent, and functional web pages and web apps while adhering to modern web design principles such as browser portability, device independence, and graceful degradation.
Important Features of Materialize CSS
	It is a standard CSS with minimal footprint.
	In-built Responsive Design
	It is free to use and requires jQuery JavaScript library to function properly. 
	It is cross-browser, compatible, and can be used to create reusable web components.
	It contains enhanced and specialized features such as cards, tabs, navigation bars, toasts etc.
	It provides new versions of common user interface     controls such as buttons, checkboxes, and text fields adapted to follow Material Design concepts.


1.2.4	 Material Design Lite (MDL)

                MDL makes it easy to add a material design look and feel to your websites. The “Lite” part of MDL comes from several key design goals: MDL has few dependencies, making it easy to install and use. It is framework-agnostic, meaning MDL can be used with any of the rapidly changing landscape of front-end tool chains. MDL has a low overhead in terms of code size, and a narrow focus — enabling material design styling for websites.
               MDL is a complementary implementation to the Paper elements built with Polymer. The Paper elements are fully encapsulated components that can be used individually or composed together to create a material design-style site, and support more advanced user interaction. That said, MDL can be used alongside the Polymer element counterparts.

1.2.5	 JavaScript (JS)
                    JavaScript is a programming language
commonly used in web development. It was originally developed by Netscape as a means to add dynamic and interactive elements to websites. JavaScript is a client-side scripting language, which means the source code is processed by the client's web browser rather than on the web server. This means JavaScript functions can run after a webpage has loaded without communicating with the server. For example, a JavaScript function may check a web form before it is submitted to sure all the required fields have been filled out.
 The JavaScript code can produce an error message before any information is actually transmitted to the server.
Like server-side scripting languages, such as PHP and ASP,      
JavaScript code can be inserted anywhere within the HTML of a webpage. 
However, only the output of server-side code is displayed in the HTML, while JavaScript code remains fully visible in the source of the webpage. It can also be referenced in a separate .JS file, which may also be viewed in a browser.
1.2.6	 System Analysis and Development (SAD)

                 To evaluate and design databases; to develop and program systems using web technologies; to carry out technical feasibility studies using criteria based on cost and efficiency to select alternatives; to administer and develop data processing projects; to administer, dimension and maintain computer networks; to work as software engineers; and to work in teaching and research.
</body>
</html>
