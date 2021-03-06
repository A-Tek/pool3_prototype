
# [![ATek Logo](https://googledrive.com/host/0B_QkjcHRJY6wS3MyUjlhY1o5SzQ)](http://www.a-tek.net/) 

# [A-TEK Inc Prototype](http://52.5.25.227/)


##**1. Summary**
A-TEK is extremely pleased to submit a proposal for the GSA Agile Services contract. We understand the detailed requirements of the IDIQ contractor. We possess the proven methodology and technology experience to support F18ís vision for executing the IDIQ and task orders. The following sections describe our Agile Approach and Technical Approach for the prototype. 
  
##**2. Prototype Methodology**

#####**2.1 Scrum Agile Approach**

Applying the Scrum Agile methodology, we designed, developed, and tested the agileTek prototype; allowing us to highlight our agile capabilities and process maturities. The following information defines the high-level Scrum methodology, we utilized for this prototype.

![Agile Process](http://googledrive.com/host/0B_QkjcHRJY6wQWJmVlBWME8weG8)
  
 We assigned a Product Manager, Agile Coach, Scrum Master, Technical Architect, UI Experts, and Developers to design, develop, and test the prototype. The Product Manager role defines the requirements, maintains and prioritizes the backlog, and approves the sprint cycles and suggestions. 
We executed this prototype in two sprints with a sprint duration of one week. As part of the first sprint, our approach included user stories, related user interface design, and technology selection. The second sprint included developing and delivering the prototype. Per our methodology guidelines, we conducted 15-minute daily-standup meetings and retrospectives at the end of each sprint. We delivered a total of 550 points for two sprints compared to the planned 600 points. Our approach also included external, assigned user roles to review and provide feedback of the prototype after each sprint. 

  
#####**2.2	User Centered Design Methodology**

As part of the iterative approach, we adopted a human-centered design methodology to identify, survey, and de?ne the prototype requirements with external users. We created user personas and user walkthroughs as part of the approach for sprint one. The following image offers a high-level user interface design approach. 

![User Centered Approach](http://googledrive.com/host/0B_QkjcHRJY6wZGRFbnlTQnhUMHM)

With our proven approach, we can design the prototype to satisfy the goals and requirements of the prototype design. We believe every improvement in the area of user experience provides a win/win situation for the clients and end users, resulting in cost reductions and productivity increases. Our design methodology included a Product Manager, Front-End Developer, and Visual Designer to create initial personas, wireframes, and visual designs. Along with low-fidelity and high-fidelity designs, we created a design style guide. 

The following defines the techniques used for our HCD approach:

* Created personas and user context storyboarding.
* Created paper designs and low-level wireframes to support storyboarding. 
* Conducted simple open-card sorting to review the navigation and design layouts.
* Included end users early in the innovation process.

We conducted basic usability testing using google website optimizer by creating simple A/B testing techniques for basic navigation for high-fidelity prototypes.


#####**2.3 Continuous Development and Integration Process**
 A-TEK understands the importance of continuous development for iterative delivery approaches. We used Docker, Jenkins, and Github open-source technologies for the setup. We deployed the setup on Amazon EC2 VPC with CloudWatch as the monitoring agent. We adopted Mocha.js to write the unit test cases for client controller classes. Refer to source code repository for unit test scripts. The following information details our CD/CI approach for this prototype.


![CD Diagram](http://googledrive.com/host/0B_QkjcHRJY6wcUZMVzZKQmNiQ1k)

##**3.	Technical Architecture**



After understanding IDIQ requirements, our expertise and open source requirements of this IDIQ, A-TEK selected node.js-based, open-source Mean stack framework for this prototype. This framework is JSON standards-based, flexible, and supported on no-sql mongo database as the backend repository. Our prototype is deployed on Infrastructure as service (IaaS) Amazon EC2 on ubuntu platform, with EC2 CloudWatch and PM2 process manager for node.js for monitoring and statistics. 

 The following provides some of the benefits of our selected tools:

* Use of end-to-end single language. 
* Fast, easy, and standards-based setup and development. 
* Support for modern browsers and responsive design to support multiple devices. 
* Flexible document-based, no-sql-based database. The following information details the high level technical architecture of the Mean stack used for the prototype. 
![Technology](http://googledrive.com/host/0B_QkjcHRJY6wVHZPM3hjRXpKVEk)

##**4. Benefits and Retrospective**

**The following provides some of the benefits of our prototype approach:**

* We demonstrated our agile and technical capabilities, while adopting continuous integration with unit tests; helping identify defects early and reduce time spent fixing dependency errors
* Our Agile approach included a user experience design; helping to create a UI design, reviewed and developed quickly 
* We proved our git and open-source capabilities with the tools and technology selection


**Following are some of the areas of improvement for our prototype approach:**
* We would have demonstrated our User Experience and Technology experience with more days allocated 
* Due to schedule restrictions, we executed only one sprint for the prototype

##**5. Installation Instructions**

### Prerequisites:

**Node.js** - Download & Install Node.js and the npm package manager. If you encounter any problems, you can also use this GitHub Gist to install Node.js.


**MongoDB** - Download & Install MongoDB, and make sure it's running on the default port (27017).


**Bower** - You're going to use the Bower Package Manager to manage your front-end packages. Make sure you've installed Node.js and npm first, then install bower globally using npm

###     Prototype Installation::

Clone the Prototype source code in the application folder


		$ git clone https://github.com/A-Tek/pool3_prototype.git
Go the Application folder rot directory and execute the following statement


 		npm install

 Run the node.js server

 		node server

 		(You can use pm2 or grunt or nodemon to run the application)


Open the browser and navigate to http://localhost:3000 to open the prototype
