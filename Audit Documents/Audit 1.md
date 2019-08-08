# Concept of Operations 
This document is issued to define our team project - Mobile insect processing plant design and state its objectives.
## Document Revision History

| Issue            | Revision         | Date             | Purpose of Issue  | Prepared by       | Reviewed by       |
| :--------------: | :--------------: | :--------------: | :---------------: | :---------------: | :---------------: |
| 01               | 00               | 03/08/2019       | Draft for Audit 1 | Jiaying Ying      | N/A                  |
| 02               | 00               | 04/08/2019       | Edit section 2&4 | Jiaying Ying      | N/A                  |
| 03               | 00               | 05/08/2019       |Edit section 1&5&6 | Minghui Zhang      |N/A                   |
| 04               | 00               | 06/08/2019       | Edit section 3  | Andre Olivier     | N/A                  |
| 04               | 01               | 08/08/2019       | Initial review  |  N/A    | Minghui Zhang                  |
| 05               | 00               | 09/08/2019       | Final review  |  N/A    | All team                  |

## Table of Content
- [1. Project Vision](#1-project-vision)
  * [1.1 Value Proposition](#11-value-proposition)
  * [1.2 Project Scope](#12-project-scope)
  * [1.3 Key Achievement](#13-key-achievement)
- [2. Relevant Stakeholders](#2-relevant-stakeholders)
  * [2.1. Project Team](#21-project-team)
  * [2.2. Project Client](#22-project-client)
  * [2.3. Third Party Supervisors](#23-third-party-supervisors)
  * [2.4. Shadow Team](#24-shadow-team)
  * [2.5. Potential Customers](#25-potential-customers)
- [3. Resources Risks and Contingencies](#3-resources-risks-and-contingencies)
  * [3.1. Project Costs](#31-project-costs)
  * [3.2. Project Outcome Risks](#32-project-outcome-risks)
    + [3.2.1. Financial Risks](#321-financial-risks)
    + [3.2.2. Material Risks](#322-material-risks)
  * [3.3. Contingencies](#33-contingencies)
- [4. Milestone](#4-milestone)
  * [4.1. Goals for Each Audit](#41-goals-for-each-audit)
  * [4.2. Contingencies](#42-contingencies)
  * [4.3. Timeline of the Project](#43-timeline-of-the-project)
  * [4.4. Work Breakdown Structure](#45-work-breakdown-structure)
- [5. Contracts](#5-contracts)
- [6. Development Tools and Management of Taks - Project Repository](#6-development-tools-and-management-of-taks---project-repository)
  * [6.1. Repository Guide](#61-repository-guide)

## 1. Project Vision 

This project aims to produce mobile and cost-effective rendering plant, capable of processing insects into meals and oils that meet regulatory requirements. The goal for this semester is to finish the designing part of the project.

### 1.1 Value Proposition 

Population increases have dramatically risen in recent years, and with it increased consumption of food. One crucial component in human's dietary structure, protein, requires people to expand the soybean cultivation to feed livestock. One alternative solution is to farm insects in order to provide an alternative food resource to livestock. Current regulations require the animal products, which are used in agriculture feeds, to be processed in modern rendering plants. However, the existing rendering plants cannot process the insects economically, due to the small-scale nature of insect farming industry in Australia. Thus, this project is aiming to design a mobile, micro processing plant which can process insects cost-effectively.  

### 1.2 Project Scope 

The project scopes are divided into three parts and summarized below.
* Design the micro-scale rendering plant based on research. 
* Use CAD software to draw the schematic drawing of the designed micro-processing rendering plant. 
* Use FEA software to simulate the working process of the plant and make sure the designed plant can technically work properly and meet the stakeholder requirements. 
* Conduct economic analysis to calculate the budget for building a prototype plant. 


### 1.3 Key Achievement 
The expected achievement in this project is designing and building a mobile and cost-effective rendering plant. It need to be able to process and convert insects into oil and meal for livestock which can meet regulatory requirements. The key achievement in this semester is to finalize the designing part of the project.

## 2. Relevant Stakeholders

### 2.1. Project Team 

This project team consists of 4 undergraduate students with different engineering skills. All the members need to follow the ground rules in the group. Each member has their distinct roles and needs to be responsible for their sections. Other external stakeholders can have direct contact with the member if they have any advice, concerns or questions toward one specific section.


| Name           | Role                  | Email                                                   |
| :------------: |:-------------:        | :-----:                                                 |
|Andre Oliver    |Mechanical engineer    | u5807603@anu.edu.au                           |
|Haoxuan Tan  | Administrator |u6391332@anu.edu.au|
|Jiaying Ying| Research and repository manager| u6034298@anu.edu.au |
|Minghui Zhang | Mechanical engineer | u6065938@anu.edu.au|

- Project team ground rules
  * All team members need to communicate and treat each other with respect.
  * All team members need to attend meetings on time. If any group members cannot attend meeting, please let others know.  
  * All team members need to value feedback from team members and other stakeholders; avoid being defensive about giving and receiving any constructive feedback.
  * All team members need to communicate task progress regularly, try to finish the assigned tasks on time based on the deadline set in the milestone. 

- Responsibilities of the Mechanism engineers to the project 
  * Finish the conceptual design based on research conducted. 
  * Use CAD software to draw the schematic diagrams of the designed mobile rendering process. 
  * Use finite-element-analysis tool (COMSOL Multiphysics) to simulate the machine-working-process and ensure the mobile plant can process insects into meals and oils that meet regulatory requirements.
  
- Responsibilities of the research and repository manager to the project 
  * Do the required technical research about the rendering process.
  * Do financial research about the whole designed rendering process and obtain the budget of the final proposed prototype.
  * Manage the repository and upload all the files and documents related to the project.
  
 - Responsibilities of administrator to the project 
   * Set and lead weekly regular group meetings.
   * Maintain contacts with clients and arrange regularly meeting between the project team and clients.
   * Document key points in each meetings and upload documentation to repository. 
   * Ensure all the project goals and milestones are achieved and not behind schedule.
  
### 2.2. Project Client

Our client is [Goterra Pty Ltd](https://www.goterra.com.au). The company is a organic waste management company. They believe that in order to make a difference, things need to be done differently. Different from other organic waste processing technologies, Goterra farms insects, especially the Black Soldier Fly, Hermetia Illucens (BSF) to consume organic waste and throughout the course of our process, harvest larvae and frass to turn them into valuable agricultural commodities. The client team members that are involved in this mobile insect processing plant design project are outlined in the table below.

| Name           | Role                  | Contact                   | Key interaction with the Project                           |
| :------------: |:-------------:        | :-----:                   | ------                                                 |
| Olympia Yarger | Founder and CEO       | olympia@goterra.com.au    | Provides the defination and objectives of the project and guides on the project progress |
| Jiefei Wang    | Robotics Engineer     | jiefei@goterra.com.au     | Provides relevant technical supervisation and assistance |
| Martin Amidy   | On behalf of Olympia  | martin.amidy@anu.edu.au   | Regularlly provides feedback and supervision during the project ongoing period and builds the connection between our project team and the project client |
 
- Responsibilities of the project team to the client
  * Design a low-cost mobile insect processing plant in regards to the client baseline requirements.
  * Regularly report the project progress and other relative information (such as reasonable delays and potential risks). 
  * According to the design, estimate a financial budget analysis (including the product lifecycle and potential cost of the build of the plant).   

- Responsibilities of the client to the project
  * To define the objectives of the project. 
  * Provide feedback to the project team timely.
  * Provide relevent and necessary technical supervision and assistance.
  * Be able to attend the regularly set meeting. 
 
### 2.3. Third Party Supervisors

The third party supervisors in the project are the course convenor and tutor of [ENGN4221](https://programsandcourses.anu.edu.au/course/engn4221) at Australian National University. The purpose of the course is to engage the students to solve a practical industrial design problem with application of the learnt systematic and techincal knowledge. Whilst doing the project, the development of communication skills, professional skills, team work management will be expected.

| Name           | Role                  | Contact                   | Key interaction with the Project                           |
| :------------: |:-------------:        | :-----:                   | ------                                                 |
| Ankur Sharma   | Course Convenor       | ankur.sharma@anu.edu.au   | Provide feedback on the different stages of the project and give systematic gudiance on how to do the project |
| Jani Sega      | Course Tutor          | jani.sega@anu.edu.au      | Provide feedback on the different stages of the project and give systematic gudiance on how to do the project | 

- Responsibilities of the project team to the third party supervisors
  * Provide the detailed information in regards to the assessment guidance about the project progress towards the milestone.
  * Attend the regular tutorials and do the presentations that talk about the project.
  * Submit the required documents on time.

- Responsibilities of the third party supervisors to the project
  * Provide feedback on the different stages of the project.
  * Provide systematic gudiance on how to do the project.
  * Estabilish the connection between the project team and project client.
  * Assist the project team to complete the project and let the project be beneficial to the client.
  * Have capacity on the communication, such as email and appointment.

### 2.4. Shadow Team

The shadow team is another stakeholder in the project, who is enroled in the same tutorial slot as our project team. The shadow team has access to review all project information and will regularly provide feedback on each stages of project. Our project progress may inspire them and their recommendations may also be useful on the improvments of the project.

- Responsibilities of the project team to the shadow team
  * Provide shadow team the required access to our team project respositories.
  * Communicate appropriately with shadow team. 

- Responsibilities of the shadow team to the project
  * Provide feedback on the project timely.

### 2.5. Potential Customers

Potential customers (and the targets) of our project product will be insect farms and other organic waste management companies. Goterra has clients from government, councils, hotels, hospitals, restaurants and households.  

Potential customers have no responsibilities to the project, but their requirements are one of the most important factors to be considered in the process of designing the mobile insect processing plant.

## 3. Resources Risks and Contingencies

Large amounts of heat, pressure and liquid are involved in the rendering process. While better manageable in a factory setting, with infrastructural ventilation and cooling, doing the same processes in a small scale space will require thorough understanding of the thermodynamic systems taking place. 
This is of course to minimize the resources needed to complete the project, the possible risks faced,  and allows accurate understanding of the contingencies needed to prevent them.

### 3.1. Project Costs

The goal of this project is to deliver a preliminary design for a movable, compact, insect meal rendering plant, with actual prototyping and final design to be completed over a "to be determined" period of time beyond 2019. The costs associated with the first stage of this process will therefore be minimal, as most of the project work will revolve around building simulated designs using different software tools, as well as conducting market research with different industry partners, and having discussions with foreign manufacturers and merchants. 

The projected budget is therefore as follows:

| Resource needed | Bearer | Estimated Cost (AUS $) |
| :-------:   | :-------  | :-------------------------------------------------- |
| Labour | ANU | N/A |
| Software Resources | ANU | N/A |
| Transport | Gotera/ANU | 50 |
| Prototyping| ANU| 500
| Total | | 550 |

### 3.2. Project Outcome Risks

The integrated nature of the final design, has with it accompanying risks that all pose their own different levels of importance. These risks can be relegated into two categories: Financial and Material Risks, each with their own set of contigencies that will aim to minimize their probability and impact.

#### 3.2.1. Financial Risks

As the categoriy suggests, these are risks that result due to poor research and design, which result in either mismanaged funds or wasted capital expenditure. 

The most significant of these are as follows:

| Risk | Description                                                  |
| :-------:   | :----------------------------------------------------------  |
| Innacurate Cost Projections | Some of the costing done of the equipment and general infrastructure of the unit will require estimates based on what information is publicly available or readily obtainable. If these project costs are innacurate, and they move through into the final design, it may end up maaking the plant too expensive too produce, with the addition ofa possible re-start near the beginning of the design process. | 
| Over-Engineered Design| A key stakeholder requirement is that the costs of the final design be kept as low as possible, and as efficient as possible. If the final design has built-in ineffcencies, this equates to over-spending on equipment, and therefore must be avoided.|
| Poorly Engineered Design | The worst case scenario in which both of the above scenarios may take place, as well as the additional issue that the final design is not fit for purpose, most likely resulting in acquisition of large amounts of capital that has no function.|

#### 3.2.2. Material Risks

These risks pertain to the physical nature of the rendering plant and its associated processes. 

| Risk | Description                                                  |
| :-------:   | :----------------------------------------------------------  |
| Inadequate Cooling | The large amounts of heat produced by the rendering process will require effective cooling methods to ensure no damage can result to the equipment integrated togethor in the confined area, while also ensuring the safety of any human operators nearby or when scheduled maintenace takes place |
| Pressure Build-Up | The confined space that the process will be housed in may result in gradual pressure build-up, due to the heat and gasses used to seperate the meal from the tallow. If left un-mitigated, damage can occur to not only the equipment housed inside the module, but also to any humans near the unit when the pressure is violently released, whether in the form of an explosion(s) or super heated gasses.|
| Inadequate Supporting Structure | The housing that the plant will be placed in needs to not only protect the equipment, but also ensure that weight distribution is even, peripheral equipment such as conveyer belts and pipes are properly supported, no piece of equipment can interfere with the function of another, and that movement of the module will not cause damage to the equipment housed inside (as mobility of the rendering plant is a key stakeholder requirement).|
| Limited Access | The design of the plant and housing needs to support accessability to the equipment and all supporting infrastructure, in order to ensure regular maintenance and repairs, minimizing some of the hazardous risks explained above.|

### 3.3. Contingencies

As demonstrated, the risks the project in general faces are widespread and feature not only in the physical space but in the financial one as well. There are therefore contingencies that need to be placed to ensure that the design process minimizes the probability of each of the afformentioned risks, ensuring the highest probability of success for the project.

Instituting key aspects into the design process is therefore crucial, with those being identified as:
<ul><li> A Central Control System: This will observe all sensor data measured in the plant to notify any operators of potential hazards that need to be mitigated. 
</li><li> Modular Design: Ensuring that any design is modular (while also fostering integration) will allow easy access, as well as assist in cooling and ventilating the plant.
</li><li> Stepped Design and Review Process: This will assure proof of concept, minimizing the financial risks mentioned, as well as producing the best overall desing that meets the stakeholder requirements.
</li></ul>

## 4. Milestone 

The following statement of milestones are drafts, they will be updated with the progress of project.

| Milestone  | Objectives| Exit Criteria                                    |
| :-------:   | :-------  | :-------------------------------------------------- |
| 1 | Communicate with client to clarify the project scope and requirements and learn about the existing issues. | <ul><li>The problem is well defined and documentated </li><li>The client needs are finalished and signed off by the client</li></ul>|
| 2 | Research on the exiting food processing plant designs and brainstone on the design ideas.                 | <ul><li>Gather the technical idea how the insect processing plant work and complete the plant system functional anlysis</li><li>Collect the information about the plant and insect, for example dimensions of each sections, such as cooker, decanter and separator and viscorsity of cooked insects</li></ul>
| 3 | Following the systematic engineering procedures, generate several possible design schemes and choose the best solutions.| <ul><li>Complete the draft deisgn schemes </li><li>Complete scenario planning to select the best design</li></ul>
| 4 | Complete the first version of the detailed design with components in each sections identified and gain the feedback from client, third party supervisors and shadow team.|<ul><li>The overall 3D design is done by using CAD with its properties detailed such as material </li><li>Complete each component design and state its functionalities</li></ul> |
| 5 | Optimise the initial design with the feedback.|<ul><li>Complete the updated design and send to the stakeholders </li></ul> |
| 6 | Validate and evaluate the design achieved the project requirements.|<ul><li>Complete pressure and heat analysis on the 3D model of the designed plant that ensure the design is achieved all of the project requirements and client needs</li><li>Complete technical importance table and evaluation matrix </li></ul> |
| 7 | Finalise the design and documentate all the information of the project back to client.|<ul><li>All documentations and repository information given to Goterra</li><li>All the CAD design files given to Goterra</li><li>Meet the client to ensure the client satification and give the general introduce on the continues work</li></ul> |

### 4.1. Goals for Each Audit
| Audit           | Time             | Goals and deliverables           |
| :-------------: | :--------------: | :--------------  | 
| Audit 01        | 09/08/2019       | <ul><li>Decide and establish the project landing page and repository</li><li>Clarify the ojectives to define project for this semester with client including problem scope, stakeholder analysis and system boundary analysis</li><li>Complete the first version of Concept of Operation document</li><li>Briefly estimate the financial budget</li></ul> |
| Audit 02        | 30/08/2019       | <ul><li>Complete systematic engineering governance, such as requirements analysis including pairwise analysis and technical performance measures, functional analysis and system architeture for the design</li><li>Do the research on the food processing plant and brainstone the design ideas</li><li>Generate and sketch several possible design schemes</li><li>Provide more detail on each section design</li><li>Update Concept of Operation document into second version</li></ul> | 
| Audit 03        | 11/10/2019       | <ul><li>Finalise the mobile insect processing plant design</li><li>Validate and evaluate the design achieved the project requirements </li><li>Documentate the estimated finanal cost on building the plant and the lifecycle of the plant</li><li>Complete the handover documentation back to the client</li><li>Complete and submit the project poster and be ready to present at the project showcase</li></ul> | 

### 4.2. Contingencies

If everything goes well and the first 7 [Milestone](#Milestone) could be completed before the set timeline, the further more complex analysis with less limitations could be achieved and a scaled-downed prototype of the designed plant is another milestone. 

The initial generated progress of the project may effect by the many unpredicable and unexpected factors. Hence, the baseline of the project is finish the CAD design of the insect processing plant with all its funcationalities identified and dimensions detailed.

### 4.3. Timeline of the Project

The Gantt Chart of the project could be found [HERE](https://github.com/JessYJY/insectfarming.github.io/blob/master/Image/Gantt%20Chart.pdf)


### 4.4. Work Breakdown Structure

| Level |	WBS code |	Element	| Duration (Days)|	Start Date|	End Date|	Responsible Person|	Dependancies	Descriptions|	Completence|
| --- |	--- |	--- 	| --- |	--- |	--- |	--- |	--- |	--- |
|1|	1	| Stretch Sense Integration	| 0 |	29/7/19	| 29/7/19	| Project team	|		
|**2**|	**1.1**|	**Concept of Operation**	|**8**	|**2/8/19**	|**9/8/19**				|
|3|	1.1.1|	Project Scope |	6	|2/8/19|	7/8/19|	Minghui Zhang	|N/a		|
|3|	1.1.2|	Stakeholder Analysis|	6|	2/8/19	|7/8/19	|Jessica Ying|	N/a		|
|3|	1.1.3|	Completion of Non-Disclosure and IP Agreements	|6|	2/8/19	|7/8/19|	Project team and Goterra|	N/a		|
|3|	1.1.4|	Estimate indictive financial budget	|6	|2/8/19	|7/8/19	|Andre Olivier|	N/a		|
|3|	1.1.5|	Risk Analysis|	6|	2/8/19|	7/8/19	|Andre Olivier	|N/a|		
|3|	1.1.6|	Setup landing page and repository |	6	|2/8/19|	7/8/19	|Project team|	N/a		|
|3|	1.1.7|	Setup milestones| 	6|	2/8/19|	7/8/19	|Jessica Ying|	N/a	|	
|3|	1.1.8|	Finalise Initiation Documentation	|2	|7/8/19	|9/8/19	|Project team	|1.1.1-1.16	|	
|**2**|	**1.2**	|**Systems engineering governance**	|	| **5/8/19**	|**30/8/2019**	|**(not specific determine yet)**|	**1.1**	|	
|3|	1.2.1	|Comfirm client needs	|5|	5/8/19	|9/8/19	|Project team and Goterra|	N/a	|	
|3|	1.2.2	|Undertake requirements analysis|	8|	9/8/19|	16/8/19	|Project team|	1.2.1	|	
|3|	1.2.3|	Undertake functional analysis	|8	|9/8/19|	16/8/19	|Project team|	1.3.1|		
|3|	1.2.4|	Brainstone the possible design schemes	|8	|16/8/19	|23/8/19|	Project team|	1.2.1-1.2.3	|	
|3|	1.2.5|	Undertake idea generation| 	8|	16/8/19	|23/8/19	|Project team	|1.2.1-1.2.4		|
|3|	1.2.6|	Undertake system architecture	|8|	23/8/19|	30/8/19|	Project team|	1.2.1-1.2.5	|	
|**2**|	**1.3**	|**Project Execution**	|	|**2/8/19**|	**11/10/19**	|**(not specific determine yet)**|	**1.1-1.2**|		
|3|	1.3.1|	Research the plant and its technologies	|12|	2/8/19	|13/8/19|	Project team|	1.2|		
|3|	1.3.2|	Sketch several possible design schemes|	11|	13/8/19	|23/8/19	|Project team	|1.2 & 1.3.1		|
|3|	1.3.3	|Fill in the detail into the sections of the selected design	|8|	23/8/19	|30/8/19|	Project team|	1.2 & 1.3.2	|	
|3|	1.3.4	|Technical analysis (pressure, heat and external force)|	15|	30/8/19	|13/9/19	|Project team|	1.2 & 1.3.3	|	
|3|	1.3.5	|Intergrate the design	|8|	13/9/19|	20/9/19	|Project team	|1.3.4	|	
|3|	1.3.6	|Optimise the intial design with feedbacks	|8|	20/9/19	|27/9/19	|All stakeholders|	1.3.5	|	
|3|	1.3.7	|Validate and evaluate the design achieved the requirements	|8|	27/9/19	|4/10/19|	Project team	|1.2 & 1.3.6	|	
|3|	1.3.8	|Finalise the design |	8|	4/10/19|	11/10/19|	Project team|	1.1 & 1.2 & 1.3.7	|	
|3|	1.3.9	|Finalise the financial budget estimation and product lifecycle|	22	|20/9/19|	11/10/19	|Project team	|1.1.4 & 1.3.8	|	
|**2**|	**1.4**	|**Project Delivery**	|	| **11/10/19**	|**18/10/19**| |		**1.1-1.3**|		
|3|	1.4.1|	Finalise Documentation|	8|	11/10/19	|18/10/19|	Project team	|1.1-1.3		|
|3|	1.4.2|	Project Handover|	0|	18/10/19	|18/10/19	|Project team|	1.4.1		|
	
![alt text](https://github.com/JessYJY/insectfarming.github.io/blob/master/Image/timeline_updated1.png)
	
## 5. Contracts 
The client specified that our team do not need to sign over non-disclosure agreement and any contract related to intellectual property. 

## 6. Development Tools and Management of Taks - Project Repository
Our team's landing page can be found [here](https://jessyjy.github.io/insectfarming.github.io/).

Both SharePoint and GitHub are used in this project as development tools. SharePoint is used to collaborate tasks together. The primary purpose of using Github is to organise, and archive finalised documentations. 
### 6.1. Repository Guide 
  
The repository for this project is divided into seven components. Click [here](https://github.com/JessYJY/insectfarming.github.io) can direct you to project repository.
- Project initiation 
  * In this section, it includes project scope, stakeholder analysis, requirement analysis, function analysis, resources risks and contingencies  
- Project Schedule 
  * This section includes the project milestone and work breakdown structure. 
- Meeting
  * This section includes all the important points discussed in each meeting, including weekly group meetings, client meetings, and any other external meetings. 
 - Audit documents
   * This section includes all the information related to each audit, including audit documents, presentations preparation, and feedback from other stakeholders in each audit tutorials. 
 - Deision log 
   * This section contains each decision-making process during the project, including background, SWOT analysis of option considered, action items and the outcomes. 
 - Research 
   * This section includes all the references that have been used in the designing and evaluating phases for the rendering process.   
 - Rendering design 
   * This section includes all the information related to the designing and evaluating the rendering plant, including the CAD drawings, simulations, and financial analysis.  
- Image
   * This section includes all the images used in each documentations. 

