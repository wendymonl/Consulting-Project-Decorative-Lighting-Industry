# Consulting-Project-Decorative-Lighting-Industry

## Introduction
This is a consulting project I did for class credit, where I implemented the 6 steps of the data analysis process to make business recommendations. WakaNINE is a decorative lighting company based in Austin, TX and they tasked us with conducting primary market research to understand the lighting specification process. This project will ultimately help wakaNINe develop marketing strategies based on current trends in the way decorative lighting fixtures are selected for commercial buildings. 

### Stakeholders

#### wakaNINE's marketing team
CEO John Cook
Marketing Team


## 1. The Ask

The main goal of this project was to help develop a data-driven strategy for increasing wakaNINE's influence in the lighting specification process. The key deliverables were to conduct primary research to understand the specification process and with findings make recommendations to wakaNINE's CEO and marketing team. Some specific areas that they wanted us to investigate included:
- finding out who the key players in the specificaiton process are
- how designers make decisions through different stages of a project
- current software used by designers to model 3D spaces for clients

#### Stakeholders in the Specification Process and their needs

![Specification Decision-Makers](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/1e7e91e71027aa2e3166c1147bdcbb695e1bdc10/specification%20stakeholders%20needs%20graphic.png)
**These categories of design professionals are the target population for our survey.**


## 2. Prepare

### Data Collection with Primary Research
We distributed a survey composed of 18 questions, including free response, rating, and multiple choice questions. We recieved 106 responses in 4 days and saved the responses as a Google Sheet. We conducted a total of 9 Zoom interviews with professionals in the design industry with the goal of gaining context on the specification process before analyzing our survey data. 


## 3. Process
 
 - First, I imported the Google Sheet into Excel, which was my tool of choice for this small dataset.
- Created a Pivot table to get counts for "Have you Specified a wakaNINE product in the past?"
- made a copy of the 'Form Responses' sheet (where all survey responses are organized in rows by name of participant and columns are each survey question) to work with while keeping the original 
- added a column named "Role Category" and manually classified the self-reported "firm and role category" into 8 role classifications - Architect, Senior Architect, Interior Designer, Lighting Designer, Senior Interior Designer, Senior Lighting Designer, Sales, and Other
  - these role classifications serve to help us investigate any patterns in the different decision-making roles in the specification process
- counted number of respondents in each role category with the COUNTIF formula
  -For example, to count the number of Architects, the following sytax was used: =countif('Form Responses-Copy'!F:F,"Architect") 
- split responses to "What could lighting manufacturers improve to make your role in specifying fixtures easier?" using the Data tab in Excel 
- copied columns containg responses to "When selecting a lighting fixture for a new project, please rank the following attributes from most to least important in making your decision from 1 to 5. (5 being the most important attribute)" into a new sheet called 'Most Important Attributes'
- created table of counts of respondents ratings of each 5 attributes using COUNTIF. The rows were the 5 attributes and the columns were 5 ranking categores.
  - Ex: COUNTIF('Full Most Important Attributes'!$C:$C, 1)					

#### Below is the table that contains the rankings for each attribute and the sums in the column

![Attributes Table](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/981e78f010d44881a8a645825c20e881a5ca44c2/Table%20of%20Ranking%20Counts.jpg)
## 4. Analyze

### 4.1 Report on Survey Sample Representation
![Survey Sample Representation](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/65ac5d8269de885fcea83437b3ede9bec03700d1/survey%20representation.png)
Our survey results are not a random sample of the population of interest because they were all volunteers for this survey. Interior designers were the most represented in our survey sample, making up over half of our responses. The next most represented roles were lighting designers, making up about 15% of our responses. Architects and sales people made up 11% and 6% of our responses respectively. The “Other” category  includes project managers, property developers, marketing specialists, controls engineers, and electrical engineers. Another 6% of the respondents did not specify their role in the specification process, though some of them stated that they were principals in their firm (but did not specify the name of their firm)
  Most of the survey respondents had not specified a wakaNINE product before, so we know the survey sample could be potential new relationships for wakaNINE.  
![Survey Sample Representation](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/0db3535033bdff51ff327e768fd9fcb4d36c144f/Have%20you%20specified%20a%20wakaNINE%20product%20in%20the%20past.png.jpg)

### 4.2 Decision-Making in the Specification Process

#### Most Important Attributes for Selecting A Lighting Feature for a project
![Importance of Each Attribute](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/8b9be138b80b6e562119a206e4e1021b8eb5a6d6/clustered%20column%20graphs-%20ratings%20of%20attributes.png)
  From the plot above we can tell that 
- **Client Requests** and **Production/Ship** times were rated as the **most important attributes** 
- **Having specified fixtures on prior projects** and **Product Company's Mission** are were rated as less important overall

I made a diverging stacked bar chart in Excel to vizualize the attributes from most to least important
![Plot of Attributes](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/981e78f010d44881a8a645825c20e881a5ca44c2/Plot%20of%20Ranking%20Counts%20with%20legend%202.jpg)

  With this vizualization it is much easier for the audience to notice the most important and least important attributes that designers consider when selecting a lighting feature.

### Which Assets are used in the various Design Stages?
![Assets Used through the process](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/0db3535033bdff51ff327e768fd9fcb4d36c144f/Assets%20used%20through%20different%20phases.png)


### 4.3 Formulate Recommendations based on findings
- **Provide technical information early on in the specification process**. 46 out of the 104 responses to the free response question "What could lighting manufacturers improve to make your role in specifying fixtures easier?" mentioned wanting more technical details early on. 

The three main categories of technical details that designers requested are:
  1. Electrical Details including LED drivers, color temperature options, driver compatibility, lumen output 
  3. Installation Information including mounting details, bulbs required for each fixture, and finish options
  4. Files for Design Software including IES files, Building information models, and Revit files
  This information should be easily available online for quick access to designers. The website could require designers to register their email to access these files. That way wakaNINE could get more designers signed up to their newsletter.
  
- **Make website searchable by technical specifications** like driver type, lumen output, color temperature, and mounting details. In interviews, designers reported that they search for decorative lighting that will fit their existing plans, so helping them easily find lighting that matches their specific needs will make easier and faster for them to put wakaNINE's products on the specification sheet.

- **Target Property Developers directly through social media ads** Design Firm clients are the most important decision-makers in the specification process (as noted in Section 4.2) If they like wakaNINE's products, they will ask the designers they hire to include them in their project. 

## 6. Share: Present Findings and Recommendations to Stakeholders

Our team presented the project deliverables to John Cook, CEO of WakaNINE, over Zoom. The short presentation included a summary of our teams methodology, analysis, and recommmendations for wakaNINE. Please note that in this repository I only included work that I produced independently. Feel free to take a look at our teams slides for further details on this project. 
[Final Presentation Slides](https://www.canva.com/design/DAEcyhbapHI/Lg2MQVS7oFezn0rUrqRqHw/view?utm_content=DAEcyhbapHI&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu)

## 7. Act- Next Steps
- With the help of our primary data collection, analysis, and recommendations, wakaNINE can make data-driven decisions for increasing sales through the Specification Process. 
- The financial team can assess how much technical information is feasible to provide on their website considering their available resources. 
- Third-party datasets can be combined with the primary data collected over the course of this project to strategically implement a data-driven approach to the specification process
- Further market research is required to investigate the differences in decision-makers preferences when choosing decorative lighting

