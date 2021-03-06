# Information System Development Methodologies

## Table of contents
1. [Problem Definition](#problemdefinition)
    1. [Objectives](#objectives)
    2. [Stakeholder List](#stakeholderlist) 
    3. [Empathy Map](#empathymap)
    4. [POV Statements](#povstatements)
    5. [How Might We Statements](#hmwstatements)
    5. [Reflection](#reflection)
2. [Prototyping and models](#models)
    1. [User Stories](#userstories)
    2. [Use Cases](#usecases)
    3. [Activity Diagrams](#activitydiagrams)
    4. [Class Diagram](#classdiagram)
    5. [Collaboration Diagram](#collaborationdiagram)
3. [Advantages and Risks](#advantagesandrisk)
    1. [Advantages](#advantages)
    2. [Effects if project were to fail](#risks)
4. [Presentation](#presentation)

## Problem Definition <a name="problemdefinition"></a>

### Objectives <a name="objectives"></a>
The travel company is planning to develop this information system in order to improve the call flow rate to the Relationship Managers(RM's). The company has a variety of holiday packages on offer because of which there are different types of requests and enquiries from customers. Relationship managers are more informed about certain destinations than others so it poses a problem when a customer is connected to a RM who has minimal knowledge of the destination they wish to enquire about leading to diverted calls and longer call time. Therefore, the main objective of the information system is to connect the customer with an appropriate RM to facilitate faster and efficient call flow. This can be achieved by implementing the Profiler Tool with the system to match the customer profile with the RM profile.

### Stakeholder List <a name="stakeholderlist"></a>
* Customers
* Relationship Managers
* System Developers
* IT Department
* Accounting Team
* Call Management Centre Owner
* Travel Destination Representatives

### Empathy Map <a name="empathymap"></a>
**Customers**

![Customer Empathy Map](https://github.com/shresthaprince/InfoSystems/blob/develop/Diagrams/Empathy%20Maps/Customer_Empathy_Map.png)

**Relationship Manager**

![RM Empathy Map](https://github.com/shresthaprince/InfoSystems/blob/develop/Diagrams/Empathy%20Maps/RM_Empathy_Map.png)

### POV Statements <a name="povstatements"></a>
#### Customer POV
* I want adequate information on the holiday packages so I can make a decision
* I want to talk to the same RM when revisiting because he understands me better
* I wish that I was connected to an RM that is more tailored to my needs and traits
* We had to wait about 30 minutes to be connected to an operator
* I want my account to be secured behind security questions
* I want someone that understands me best
#### RM POV
* I wish our system was able to integrate booking sites for hotels, tours and travel all in our system
* I had to reconnect 3 callers to other RM’s today because I did not know much about their desired destinations
* I want more details about the customer’s information available when getting calls
* It would be nice to prioritise customers based on how likely they are to purchase more packages
* It would be great if we get connected to customers who are enquiring about destinations we are familiar with
* I want our systems to retrieve customers security question and responses when they try to access 
* I would like the profiler tool to be editable as we learn more and more about the customer for future reference
* I want to be given more profiling options for customers in order to better serve them
* I want to be able to rate customers based on their experience and leave comments if they were disrespectful

### How Might We Statements <a name="hmwstatements"></a>
* How might We make our systems Streamlined for greater efficiency?
* How might we make our system more timely?
* How might we connect customers to relevant RM’s?
* How can we provide more details about our customer’s for our RM’s?
* How might we ensure customer account details are secure?
* How might we maintain a future proof system for RM’s in the future? 
* How might we ensure our system matches us with the right people?

### Reflection <a name="reflection"></a>
* Assuming that RM's are able to sort Profiler tool by what they believe they are confident in. As the questionaire is only completed upon hiring --> RM's may have learnt about new information making them confident with a different demographic
* Assuming that Hotels/Tours/Accomodation sites are integrated within systems allowing a reduced caller wait time and a smoother customer interaction
* Assuming that the interactive voice assistant is able to decipher and analyse the customer profile → Put through to relevant RM with experience
* Assuming that RM’s are able to see a set of transaction history, quote history, and geographic preferences of customers, that will provide RM’s with a suggestion of destinations that match the customer the most. Increasing the chances of the sale going through.
* We have decided to focus on two stakeholders which is the RM and the customer to make it easier for us to evaluate their roles
* We decided that we would each add a few dot points into every aspect of the empathy map to make the workload easy and fair
* We assumed the roles of each stakeholder and imagined their conversation and interaction to come up with the empathy map
* We used personal experience as a caller to come up with POV’s for the customer
* We came up with a list of stakeholders such as Customers, RM’s, Developers and decided to focus on Customer and RM’s as they are the most relevant
* We made the assumption that the old system was not able to handle multiple inbound calls in an efficient way and was not able to allocate customers based on likelihood of purchase
* We used personal work experience when thinking of the relationship managers POV

## Prototyping and models <a name="models"></a>

### User Stories <a name="userstories"></a>

#### Customer
* As a customer, I want to be connected to a RM that has knowledge about my destination so that I can make an informed decision.
* As a customer, I want to receive Itinerary and transaction details automatically sent to my email address once the sale has been completed So that I can have a seamless experience. 
* As a customer, I want to be able to be removed from the target list, so that I do not get interrupted during the day.
* As a customer, I want to talk to the same Relationship Manager so that I can have consistency when talking about travelling. 
* As a customer, I want to have a transcript of our conversation sent to my email so that I have information on all the questions I asked and won’t need to ask them again
* As a customer, I want to be connected to a Relationship Manager in as little time as possible so that I don’t have to wait on hold for too long.

#### Relationship Manager

* As a RM,  I want as much information I can have about the caller so that I can provide relevant information and reduce the call duration.
* As a RM,  I want my target list to have products I know and customers that match with my profile so that I can increase my chances of selling the product.
* As a RM,  I want a script that is designed for the particular customer target list so that I can connect better with the customer.
* As a RM,  I want my inbound calls to have a score from 1-10 so that I can see how likely they are to make a purchase. 
* As a RM,  I want to be able to update my RM Profile as I learn new information so that I can provide the highest level of customer service to my customers.
* As a RM,  I want to be able to view and compare prices of listings so that I can provide the customer with information in a fast and efficient manner. 
* As a RM,  I want customers to be segmented into social and cultural groups so that I have a better chance of relating to them to get the sale. 

### Use Case Diagrams <a name="usecases"></a>

#### Inbound Calls
![User Story-Inbound](https://github.com/shresthaprince/InfoSystems/blob/develop/Diagrams/Use%20Case%20Diagrams/Inbound.png)
#### Outbound Calls
![User Story-Outbound](https://github.com/shresthaprince/InfoSystems/blob/develop/Diagrams/Use%20Case%20Diagrams/78126059_247711966328847_4216616372282589184_n%20(1).jpg)

### Activity Diagrams <a name="activitydiagrams"></a>

#### Inbound Calls
![Activity Diagram-Inbound](https://github.com/shresthaprince/InfoSystems/blob/develop/Diagrams/Activity%20Diagrams/Inbound%20Acivity%20Diagram.jpeg)
#### Outbound Calls
![Activity Diagram-Outbound](https://github.com/shresthaprince/InfoSystems/blob/develop/Diagrams/Activity%20Diagrams/Outbound%20Activity%20diagram.png)

### Class Diagram <a name="classdiagram"></a>
![Class Diagram-Outbound](https://github.com/shresthaprince/InfoSystems/blob/develop/Diagrams/Class%20Diagram/RM%20Customer%20Class%20Diagram%20(3).png)


### Collaboration Diagram <a name="collaborationdiagram"></a>
![Collaboration Diagram-Outbound](https://github.com/shresthaprince/InfoSystems/blob/develop/Diagrams/Collaboration%20Diagram/Collaboration%20diagram.jpg)

## Advantages and Risks <a name="advantagesandrisk"></a>

### Advantages <a name="advantages"></a>

* Greater market share within the travel booking service industry
* Higher customer satisfaction due to streamlined and smooth processes
* RM’s have greater satisfaction rates with their work as they are able to perform their tasks and duties with more ease
* Reviews and ratings of services will result in more positive feedback
* Travel company will generate more revenue as market share grows with positive reviews
* Cost of call centre reduced with the load bearing of interactive voice response unit
* Reduced overhead as customers wishing to go to certain destinations will be directed to RM’s that are experienced in certain destinations will be able to close sales much more quickly and efficiently freeing up resources for the next caller.
* With the database accumulated regarding customer information, future calls outbound calls will yield higher success rates of closing sales thus generating greater returns.
* Over time, the database will grow with RM’s adding key information about specific customers in case a new RM has taken over since the previous RM had left the company
* As the company grows its market share, tour and hotel vendors will likely reach out in trying to gain a partnership which could generate a higher return
* When RMs have higher success rates due to the improved system, it improves workplace morale as their jobs are easier and are generating positive outcomes
* Increased customer satisfaction leads to positive customer reviews of the company which generates further revenue and increased amount of users
* Improved flow of inbound and outbound calls will lead to higher satisfaction rates with customer's and system will run more smoothly


### Effects if project were to fail <a name="risks"></a>

* This could cause severe losses in revenue due to downtime
* It could affect how customers perceive the company as a whole as “unreliable”
* Could potentially cause customers to leave this travel company and move to a direct competitor
* If the implementation of these changes in information system were to fail RM’s could be upset due to lost commissions
* If it were to fail, upfront costs would be required to either revert back to older system features or invest more into finding a solution
* If the project fails, the money invested into improving systems will have to be written off as a loss 
* Is timely to the organisation
* May cause demotivation within the organisation for relationship managers 
* Company will have to restart in trying to create another effective system - wasting more time and money 
* Customer satisfaction falls and results in less business
* Could result in negative customer reviews further reducing the likelihood to increase their user base
* If it fails, customers could start to question the reliability of the service as a whole
* If characteristics are mapped out incorrectly, it could result in errors in the system which may take time to realise and could result in long-term problems

## Presentation Video Link <a name="presentation"></a>

--> https://www.youtube.com/watch?v=YhYWj1OSWkE
