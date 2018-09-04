

A PROJECT REPORT ON

“Electronic Thesis and Dissertation”

FOR

GMIT

SUBMITTED IN PARTIAL

FULFILLMENT OF INTERNSHIP

PROJECT

UNDER THE GUIDANCE OF

Director

Mr. Ravi Chhabra

Supervisor

Dr. Daw Khaing Moe San

**SUMITTED BY**

    Ma Ei Mon Theint
    Ma Khaing Nyo Thein
    Ma Shwe Zin Oo
    Ma Nann Khaing Zar Thinn
    Ma Yun Me Me Thaw
    Ma Ei Cho Zin

**University of Computer Studies (Mandalay)**

**Abstract**

This project will present how to search thesis data and suggestions via online. Users can browse search button by author’s name, year, title or degree and then the related answers will be received. Admin can insert up-to-date data, delete unnecessary data and update thesis data.

For Front End, the project will be implemented by using HTML, Materializecss, Material Design Lite and JavaScript. For Back End, the system was implemented by using Real-Time Database of Firebase and JavaScript.

**ACKNOWLEDGEMENT**

We would like to express our very great appreciation to our Rector U Kyaw Zwa Soe , for his kind permission to send us internship Program. Then, we would like to express any special thanks to Dr. Daw San San Tint , Pro-Rector, for her helpful recommendations and suggestions. And then our teacher Dr. Daw Khaing Moe San, Associate Professor , for her valuable and constructive suggestions during the planning and development of this project. They willingness to give their time so generously has been very much appreciated. Advice given by other academic lectures has been a great help in building the software solution.

Also we obliged to staff members of University of Computer Studies (Mandalay) for the valuable information provided by them in their respective fields. We are grateful for their cooperation during the period of developing the system. Assistance provided infinity software development crew was greatly appreciated. Their contribution was worth a lot, in making this development a reality.

Then also thanks to Mr. Ravi Chhabra , CEO of GMIT, for his trust to give us such a heavy responsibility project.

We especially thanks to our parents and all our friends for providing encouragement and giving us a great support during internship programme.

**DECLARTATION**

We declare that this project report or part of it was not a copy of a document done by any organization, university any other institute or a previous student project group at University of Computer Studies (Mandalay) and was not copied from the Internet or other sources.


Project Details

Project Title  Electronic Thesis and Dissertation System

Project ID     Geo-Mandalar Investment & Technology Internship


**Chapter 1**

**Introduction**

**1.1	Introduction**

Nowadays, Mobile phones are very useful for everyone to communicate with each other. So, they are becoming an important part of our everyday life. Nowadays, reducing the men’s physical effort with the help of latest devices and technologies is on demand. The project provides us the complete and accurate information about thesis.
The project named “Electronic Thesis and Dissertations System” is aimed to search easily thesis data. The project is developed for window side and mobile phones. Our project mainly focuses on basic operations like inserting new data, updating or deleting existing data, view thesis data and so on. This project has many advantages that to reduce users wait times, accessible from anywhere at any time and do not need storage space in libraries.
This project has the lists of titles, authors, year and degree on the website to find collections of thesis. Each collection has a short description to help users decide which one to use.
Our project is very useful for users who want to save their times, who can search easily data that users want to know and manual actions of the thesis for both users and admin.



**1.2	Background of the System**

**1.2.1 Evaluation of the literature relevant to the project area**

We have to consider about the method, approach, programming language and tools in developing the project. Methodology will be used as I structure the project plan; it will represent how the project will be processed. Thus we structure the project's framework, we need to consider about the project development. In the project area, we can use HTML, Materializecss, Material Design Lite, JavaScript, Real-Time database of firebase and SAD. We must use UML technique to propose the business processes in the project area; we can define the process notations by using UML diagrams. In order to code the program, we can use many computer languages.

**1.2.2 HTML**

HTML is a computer language devised to allow website creation. These websites can then be viewed by anyone else connected to the Internet. It is relatively easy to learn, with the basics being accessible to most people in one sitting; and quite powerful in what it allows you to create.
              The definition of HTML is **HyperText Markup Language.**

HyperText is the method by which you move around on the web — by clicking on special text called hyperlinks which bring you to the next page. The fact that it is hyper just means it is not linear — i.e. you can go to any place on the Internet whenever you want by clicking on links — there is no set order to do things in.

Markup is what HTML tags do to the text inside them. They mark it as a certain type of text (italicised text, for example).

HTML is a Language, as it has code-words and syntax like any other language.



**1.2.3	 Materializecss**

Materialize CSS is a UI component library which is created with CSS, JavaScript and HTML. It is created and designed by Google. Materialize CSS is also known as Material Design. It is a design language which combines the classic principles of successful design along with innovation and technology. Google's goal is to develop a system of design that allows for a unified user experience across all their products on any platform. It is used to construct attractive, consistent, and functional web pages and web apps while adhering to modern web design principles such as browser portability, device independence, and graceful degradation.

**1.2.4	 Material Design Lite (MDL)**

MDL makes it easy to add a material design look and feel to your websites. The “Lite” part of MDL comes from several key design goals: MDL has few dependencies, making it easy to install and use. It is framework-agnostic, meaning MDL can be used with any of the rapidly changing landscape of front-end tool chains. MDL has a low overhead in terms of code size, and a narrow focus — enabling material design styling for websites.
MDL is a complementary implementation to the Paper elements built with Polymer. The Paper elements are fully encapsulated components that can be used individually or composed together to create a material design-style site, and support more advanced user interaction. That said, MDL can be used alongside the Polymer element counterparts.

**1.2.5	 JavaScript (JS)**

JavaScript is a programming language commonly used in web development. It was originally developed by Netscape as a means to add dynamic and interactive elements to websites. JavaScript is a client-side scripting language, which means the source code is processed by the client's web browser rather than on the web server. This means JavaScript functions can run after a webpage has loaded without communicating with the server. For example, a JavaScript function may check a web form before it is submitted to sure all the required fields have been filled out.
 The JavaScript code can produce an error message before any information is actually transmitted to the server.
Like server-side scripting languages, such as PHP and ASP,      
JavaScript code can be inserted anywhere within the HTML of a webpage. 
However, only the output of server-side code is displayed in the HTML, while JavaScript code remains fully visible in the source of the webpage. It can also be referenced in a separate .JS file, which may also be viewed in a browser.

**1.2.6	 System Analysis and Development (SAD)**

To evaluate and design databases; to develop and program systems using web technologies; to carry out technical feasibility studies using criteria based on cost and efficiency to select alternatives; to administer and develop data processing projects; to administer, dimension and maintain computer networks; to work as software engineers; and to work in teaching and research.


**1.2.7	 UML**

Unified Modeling Language (UML) is used as to illustrate the object oriented systems and presentations. UML is a general architectural structure. It is derived from three notations; OMT (Object Modeling Technique). OOD (Object Oriented Design) and OOSE (Object Oriented Software Engineering). UML has a set of connectors and signs to use for drawing the diagrams. These diagrams can represent the business processes and functions from the companies or organizations by using UML. So, we can model the computer code and program by using these diagrams. We can know about the business processes ideas by using UML diagrams in the project.
In this project, we use Use Case Diagram to describe a set of actions that can perform in collaboration with one or more external users of the system. We use sequence diagram to show object interactions arranged in time sequence.

**1.2.8 What is Database?**

A database is a collection of information that is organized so that it can be easily accessed, managed and updated.
Data is organized into rows, columns and tables, and it is indexed to make it easier to find relevant information. Data gets updated, expanded and deleted as new information is added. Databases process workloads to create and update themselves, querying the data they contain and running application against it.
Computer database typically contain aggregations of data records or files, such as attendance transactions, attendance percentage and reports.
Typically, a database manager provides users with the ability to control read/write access, specify report generation and analyze usage. Some databases offer ACID (atomicity, consistency, isolation, durability) compliance to guarantee that data is consistent and that transactions are complete.


**Real-Time Database**

A real-time database (RTDB) is a data store whose operations execute with predictable response, and with application-acceptable levels of logical and temporal consistency of data, in addition to timely execution of transactions with the ACID properties. A real-time database is a database system which uses real-time processing to handle workloads whose state is constantly changing. This differs from traditional databases containing persistent data, mostly unaffected by time. For example, a stock market changes very rapidly and is dynamic.

**1.3 Objectives of the Project**



    To develop Electronic Thesis and Dissertations System

    To be accessible from anywhere at any time

    To learn about electronic document preparation and digital libraries

    To access multiple users simultaneously at one Electronic Thesis and Dissertations

    To search easily and save time


**1.4 Scope of Proposed System**

    The proposed project of Electronic Thesis and Dissertations is prescribed as follow:

    Manage thesis data, user's feedbacks, user's search
    
    View thesis data
    
    Send questions and feedbacks
    
    View details by authors, year ,title and degree
    
    Search easily thesis data


**CHAPTER 2**

**METHDOLOGY**

**2.1 Requirement Analysis**

The description of the services and constraints are the requirements for the system. Requirement Analysis is the process of deriving the system requirements through observation of existing system. We get all information of data we use in this project from our library.
     
**Group Interview**

Interview is the most common technique for collecting required information. Group interview is same as the one-to-one interview but more than one person at the same role can be involved in Group Interview. We go to libraries and meet all staff to make group interview. We discuss with them; what they need and how they are operating the trading process with clients in manual system. We ask them open-ended question to get requirements and then ask probing question for uncovering requirements.

**Questionnaire**

Questionnaire is one the information gathering techniques and it is informal technique. We use this technique to gather required information about staff from Library. We have some questions to ask about thesis and we have not enough time to interview with each staff to collect requirements, so we use questionnaire tool.

**Follow People Around**

We cannot understand about make assign to staff at the Library. So we need to watch how they can be assigned schedule for repair thesis books. Someday, we also participate in the actual work process to get complete understanding about the staff assign at the library.

**Evidence of Requirements Analysis**

In analysis requirements from Library, we made use information gathering tools to collect required data. These gathering tools are Group Interview, Questionnaire and Follow People Around. I will represent evidences during analyzing requirements data for developing project.

**Evidence form Group Interview**

We make group interview with staff from Library. We discuss about normal thesis in manual system. In the interview, we ask them what they need for the new computerized system and take a note to make requirement lists of different perspectives from each staff. The following sheet will represent requirement list.

**Evidence form Questionnaire**

We ask staff from Library, how thesis books are assigned in the manual system. We ask them the staff’s assign process with a few questions and write down the paper. We also request staff data entry form as a requirement of staff registration. This helps us to develop the system design easily. The following papers will show how staff can be assigned.
 
**2.2 Software Selection**

**Chosen Programming Language**

We would like to use HTML, Materializecss, Material Design Lite and JavaScript in our project because there are a lot of benefits. Material Design is a design language developed by Google. 

    They can simply code and it can be very easy to develop and can be reformed very quickly.
    
    They are particularly available and have multiple extensions.
    
    They are very popular so we can find many references and guidelines from the internet.
    
    They are readily available and easy to access.

**Software Requirements**

    
    Notepad++
    Firefox

**Hardware Requirements**

    At least 4.0 of Android OS version Devices (Android phones or tablets)

    Internet Access

    PC with Windows OS


**2.3 Project Plan**
 

In understanding the system requirements and testing some features, we work together. GUI/Database Analysis and Design, we work together. User Access Level/Access to pages, Project Manager and System Analysis are discussed about the system to understand the user.
Recording all transaction in DB, Database Administrator recorded in database tables and assigned primary key and foreign key. Generating reports, Developers generated our system and wrote the coding. Module Testing, we work together.
Integration, we work together. Integrated System Testing, we work together. Project Fulfillment Assessment Preparation, we work together, Extra Feature and Final Testing, we work together. 


**CHAPTER 3**

**EVALUATION AND CONCLUSION**

**3.1 Conclusion**

The system provides simple and complete functions for admin without necessarily change all patterns when there is some change. Beyond our purpose, the system may provide the easiest searching way for users.
Users do not need to go library for search data and they can save time. Moreover, the system can be accessible from anywhere at any time if users have internet connection and mobile phone or tablet.
Thus, Electronic Thesis and Dissertations will not only a great way for users but also one of the useful mobile and tablet applications in mobile and tablet application world.

**3.2 Advantages of the Project**

The proposed system offers the following advantages:

    To be accessible from anywhere at any time.
    
    To learn about electronic document preparation and digital libraries.
    
    To access multiple users simultaneously at one ETD.
    
    To reduce storage space in libraries.
    
    To search easily and save time.

**3.3 Disadvantages of the project**

    The cost of computer hardware and software programs can be expensive.
    
    As mobile tables use wireless network, they can disconnect with network if Wi-Fi fails.
       

**3.4 Further Extensions**

This application is suitable for students who are exploring project samples and trying to finish their research. This application has incompleteness from various view-points. But if it is continuously developed with experts, current needs will be covered shortly, then the effectiveness will approve its property. Various functionalities can be embedded within the application, if completely added those functions, the current goal of the app will be wide enough to take place of current ETD system.

	
**References**

•	Thesis Books from Computer University Library

•	www.cumandalay.edu.mm

•	https://en.wikipedia.org/wiki/HTML

•	https://www.javatpoint.com/what-is-materialize-css

•	https://getmdl.io/

•	https://www.makeuseof.com

•	https://en.wikipedia.org/wiki/real-time

**Appendices**

Appendix A: Flow Chart

Appendix B: Use Case and Sequence Diagram


