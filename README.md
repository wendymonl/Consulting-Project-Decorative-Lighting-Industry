# Consulting-Class-Project-Decorative-Lighting-Industry
## Summary
For my capstone project to obtain my B.A. in Human Dimensions of Organizatins, I implemented the 6 steps of the data analysis process to understand the specification process: Ask, Prepare, Process, Analyze, Share, and Act. This was a team project where I collaborated with 5 classmates, and this respository is meant to document only my independent contributions to the project. The ultimate goal of this project was to generate data-driven and actionable recommendations for increasing influence among industry stakeholders. 

- Conducted primary research to understand key deliverables and decision-making considerations of customers through different stages of the specification process in commercial building design projects. Methods were:
   - secondary research on the specification process to understand best-practices and steps of the process
   - An email survey campaign to investigate customer decision process
   - subbject-matter interviews to understand context behind data
- Used Excel to clean and analyze survey responses from over 100 individual customers and create data visualizations
- Presented data-driven insights and actionable recommendations on increasing influence in the decorative lighting market to the CEO 

## Introduction
WakaNINE is a decorative lighting company based in Austin, TX and they tasked us with conducting primary market research to understand the specification process. The specification process is the steps design firms take to develop concepts, document, analyze and explain decision-making to ensure that the needs and performance requirements of the client are met. I have not included anyones name or any personal information in this repository. 

### Stakeholders

- CEO of wakaNINE, John Cook
- wakaNINE Marketing Team


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


## 3. Process and Clean Data Contained in a Spreadsheet
 
- First, I imported the Google Sheet containing survey responses into Excel, which was my tool of choice since this is a small dataset.
- made a copy of the survey response sheet (where all survey responses are organized in rows by name of participant and columns are each survey question) to work with and  backing up the original 
- checked for spelling errors and corrected spelling mistakes

## 3.1 Using a Pivot Table to Count Responses to "Have you Specified a wakaNINE product in the past?"
- Created a Pivot table to get counts for designers who had worked with wakaNINE before
![image](https://user-images.githubusercontent.com/47668478/148243818-9e6da7e0-0830-4292-ae00-9cee12bb66c3.png)

## 3.2 Using COUNTIF to calculate how many respondents worked in different design roles

- added a column named "Role Category" and classified the self-reported "firm and role category" into 8 role classifications - Architect, Senior Architect, Interior Designer, Lighting Designer, Senior Interior Designer, Senior Lighting Designer, Sales, and Other
  ![image](https://user-images.githubusercontent.com/47668478/148504913-6cf2f77a-1c59-4ad1-9b6f-08a0d49669af.png)
- Then I calculated frequency of respondents in each role category with the COUNTIF formula
  - For example, to count the number of Architects, the following sytax was used: =countif('Form Responses-Copy'!E:E,"Architect") 

## 3.3 Delimiting  by Commas and Creating a new Sheet for non-multiple choice answers
- split responses to "What could lighting manufacturers improve to make your role in specifying fixtures easier?" using the Data tab in Excel to deliminate by comma
- trimmed column headers of brackets and unnecessary text 
- Added a new sheet called 'Most Important Attributes' and copied columns containing responses to question "When selecting a lighting fixture for a new project, please rank the following attributes from most to least important in making your decision from 1 to 5. (5 being the most important attribute)" 
- created table of counts of respondents ratings of each 5 attributes using COUNTIF. The rows were the 5 attributes and the columns were 5 ranking categores.
  - Ex: COUNTIF('Full Most Important Attributes'!$C:$C, 1)					

#### The Table Below contains the rankings for each attribute and sums to verify that there are no errors

![Attributes Table](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/981e78f010d44881a8a645825c20e881a5ca44c2/Table%20of%20Ranking%20Counts.jpg)
## 4. Analyze

### 4.1 Report on Survey Sample Representation
![Survey Sample Representation](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/65ac5d8269de885fcea83437b3ede9bec03700d1/survey%20representation.png)

Our survey results are not a random sample of the population of interest because they were all volunteers for this survey. Interior designers were the most represented in our survey sample, making up over half of our responses. The next most represented roles were lighting designers, making up about 15% of our responses. Architects and sales people made up 11% and 6% of our responses respectively. The “Other” category  includes project managers, property developers, marketing specialists, controls engineers, and electrical engineers. Another 6% of the respondents did not specify their role in the specification process, though some of them stated that they were principals in their firm (but did not specify the name of their firm)
  Most of the survey respondents had not specified a wakaNINE product before, so we know the survey sample has many potential new relationships for the company.  
![Survey Sample Representation](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/0db3535033bdff51ff327e768fd9fcb4d36c144f/Have%20you%20specified%20a%20wakaNINE%20product%20in%20the%20past.png.jpg)

### 4.2 Decision-Making in the Specification Process

#### Most Important Attributes for Selecting A Lighting Feature for a project
![Importance of Each Attribute](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/8b9be138b80b6e562119a206e4e1021b8eb5a6d6/clustered%20column%20graphs-%20ratings%20of%20attributes.png)
  
  From the plot above we can tell that 
- **Client Requests** and **Production/Ship** times were rated as the **most important attributes** 
- **Having specified fixtures on prior projects** and **Product Company's Mission** are were rated as less important overall

I then made a diverging stacked bar chart  in Excel to better vizualize the attributes from most to least important
![Plot of Attributes](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/981e78f010d44881a8a645825c20e881a5ca44c2/Plot%20of%20Ranking%20Counts%20with%20legend%202.jpg)

With this diverging stacked bar vizualization, it is much easier for the audience to notice the most important and least important attributes that customers consider when selecting a lighting feature.

#### Which Assets are used in the various Design Stages?
![Assets Used through the process](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/0db3535033bdff51ff327e768fd9fcb4d36c144f/Assets%20used%20through%20different%20phases.png)

- The most used assets throughout the whole process are the specification sheet and budget pricing
- The Presentation phase of the specificiation process is when designers meet with their clients to approve plans including the lighting selection. In the presentation phase, the most used assets are Finish/Material and Brochure/Catalog
- CAD File, IES File, and Line Drawings are all files that can be imported into 3D-modelling software. I learned from interviews with designers that experienced designers don't need to use these to choose decorative lighting fixtures, but junior designers might use them. That could explain why they are the least used assets throughout the specification process.

### 4.3 Formulate Recommendations based on findings
- **Provide technical information early on in the specification process**. After seperating the responses to the free response question"What could lighting manufacturers improve to make your role in specifying fixtures easier?" by deliminating commas, 46 out of the 106 responses wanted more technical details early on in the specification process.  The three main categories of technical details that designers requested in response to this question are:
  1. Electrical Details including LED drivers, color temperature options, driver compatibility, lumen output 
  3. Installation Information including mounting details, bulbs required for each fixture, and finish options
  4. Files for Design Software including IES files, Building information models, and Revit files

  This information should be easily available online for quick access to designers. The website could require designers to register their email to access these files. That way wakaNINE could get more designers signed up to their newsletter. 
  
- ***Limitations of this recommendation***: 
The information that lighting specifiers seek is not always easy for decorative lighting manufacturers to provide. For example, providing IES files for all the   different variations of their fixtures would be difficult since even changing the paint finish would affect the photometric output. To produce these files, a company has to run photometric tests of every variation of their fixtures themselves or hire an independent lab. 
   
#### Actionable Recommendations
- **Make website searchable by technical specifications** like driver type, lumen output, color temperature, and mounting details. In interviews, designers reported that they search for decorative lighting that will fit their existing plans, so helping them easily find lighting that matches their specific needs will make easier and faster for them to put wakaNINE's products on the specification sheet.

- **Target property developers directly through social media ads** Design Firm clients are the most important decision-makers in the specification process (as noted in Section 4.2) If they like wakaNINE's products, they will ask the designers they hire to include them in their project. 

## 5. Share: Present Findings and Recommendations to Stakeholders

Our team presented the project deliverables to John Cook, CEO of WakaNINE, over Zoom. The short presentation included a summary of our teams methodology, analysis, and recommmendations for wakaNINE. In this repository, I only included work that I produced independently, but feel free to take a look at our slides on Canva for further details on this project. I loved working with a team because we all brought different backgrounds and areas of expertise to our analysis. I'm proud of the way our presentation came together visually, as you can see in the canva slides.
[Specification Team Final Presentation Slides](https://www.canva.com/design/DAEcyhbapHI/Lg2MQVS7oFezn0rUrqRqHw/view?utm_content=DAEcyhbapHI&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu)

## 6. Act: Next Steps
- With the help of our primary data collection, analysis, and recommendations, wakaNINE can make data-driven decisions for increasing success throughout the Specification Process. 
- The creation of some of the technical files requested by designers is expensive, so feassibility of providing these files is up to the financial team to decide.
- Third-party datasets can be combined with the primary data collected over the course of this project to strategically implement a data-driven approach to marketing wakaNINEs products. For example, using publicly available decorative lighting sales data to make predictions on future trends in the market.

### Reflection:
I enjoyed collaborating with fellow HDO seniors on this project! Three of my team members went on to become HR professionals upon graduation, one is doing sales for Facebook, and one went on to Harvard Law. Personally, seeking a job at a small company as a backend developer or data engineer. For this capstone project, I felt lucky collaborate with a team of talented and dependable group facilitators, communicators, and project managers. 
**Below is a screenshot of the email my professor sent me containing peer reviews for me on this project**
![My Professor emailed me feedback from my peers on this project](https://github.com/wendymonl/Consulting-Project-Decorative-Lighting-Industry/blob/bc51ca1fb0777334ede84c74de5bf73ed64cbcca/Specification_Project_Peer_Feedback.png)
