# R Shiny Portfolio – [Giannis Elmatzoglou]

Welcome to my R Shiny portfolio!  
  
The following projects were created in order to enhance clinical data review.
Being based on SDTM/ADaM datasets, the goal was to make it easier for the user to explore efficacy/safety/patient data dynamically instead of relying on static tables.  

They include: interactive exploration of baseline characteristics, patient-level views, adverse event exploration with filters, lab trend visualizations and disposition data.    
  
Datasets used are publicly available.

## Projects



### 1. Building Dashboard for the Exploration of Clinical Study [December 2025]
🧠 Description  
Developed as part of the “Data Visualization & Dashboarding with R” specialization (Johns Hopkins University, Coursera, Nov–Dec 2025)

🎯 Purpose 
Interactive dashboard that creates various outputs, using pilot ADaM data.
Contains many sub-apps, inclucing:  
  -Safety Monitoring: (Adverse Events / Laboratory Tests - Shifts)  
  -Time-to-Event Analysis (Kaplan-Meier)  
  -Recruitment demographics / Subjects' Disposition details  

🌐 Live App  
[App Link](https://ioannis-elmatzoglou.shinyapps.io/clinical_study_demo/)


---

### 2. Automating Demographic / Baseline tables   [April 2026]
🧠 Description  
Interactive dashboard that creates Demographic type of tables + Listings, using ADSL dataset, uploaded by the user.

🎯 Purpose   
Automating demographics' type of tables/listings with a R-Shiny app

📊 Details  
Input fields (treatment variables, filters, variables to display) are automatically populated based on ADaM naming conventions.

⚡ Performance   
  Execution time: Instant  
  Interactivity: High  
  Automation: High  
  Applicability: Multiple Studies  
  User Expertise: Not Required  
         
🌐 Live App  
[App Link](https://ioannis-elmatzoglou.shinyapps.io/demographics/)

🎥 Demo Video  
[watch video](https://youtu.be/TaZbJ1A2hKo)

📦 R libraries used:  
-tidyverse (dplyr)  
-shiny  
-haven  

---

### 3. Automating Safety Monitoring during the study (Upgrading previous app) [May 2026]

🧠 Description  
Interactive dashboard that creates Demographic type of tables + Listings, using ADSL dataset, uploaded by the user.

🎯 Purpose   
Enable dynammic exporation of Adverse Events through an automated process, during the course of the study 

📂 Input Dataset  
A CDISC-compliant OCCDS analysis dataset of SubClass ADVERSE EVENT (e.g. ADAE)

📊 Details  
Input fields (treatment variables, filters, variables to display) are automatically populated based on ADaM naming conventions.

💡 Rationale  
Leveraging the standardized ADaM structure for AE analysis datasets, combined with the recurring need for safety monitoring and relatively straightforward outputs, makes this app an ideal option for automation

🚀 Key Advantages
✅ Interactive exploration — no more scrolling across 
   multiple PDF pages
✅ No need for traditional TFL delivery packages 
   (access via a simple link)
✅ User-friendly interface
✅ High reproducibility across different study time 
   points (e.g., DSUR meetings) with minimal or no 
   programming support
   
🌍 Applicability  
Multiple studies — currently tested on 
parallel study designs
         
🌐 Live App  
[App Link](https://ioannis-elmatzoglou.shinyapps.io/demographics/)

🎥 Demo Video  
[watch video](https://www.youtube.com/watch?v=dRcNZoTPVIc)

---

### 4. Disposition Shiny App   [June 2026]

🧠 Description 
A single-view exploration tool for subject disposition data.

🎯 Purpose
A single-view exploration tool for subject disposition data, designed to streamline clinical data review workflows.

💡 Rationale
Exploring subject disposition data often requires navigating multiple SDTM datasets at the same time. This application consolidates key information into one interface, enabling faster and more intuitive review of subject-level outcomes.

✅ Key Features & Advantages

- **Integrated View** — Displays the most important subject disposition information in a single, unified interface
- **TFL Programming Support** — Helps identify inconsistencies or conflicts in data during programming
- **Study Overview** — Provides sponsors with an overview of study disposition by subject, site, or treatment arm
- **Diagnostic Layer** — Adds an additional layer for detecting potential data or programming issues (e.g., dates, visits, epochs, treatments)

🧬 Data Source

This application uses **CDISC Pilot Study SDTM data**.

🔗 [CDISC Pilot Project](https://github.com/cdisc-org/sdtm-adam-pilot-project)

🌐 Live App   
[Launch the App](https://ioannis-elmatzoglou.shinyapps.io/disposition/)

📁 Source Code  
[View Repository](https://github.com/Bengas661/Disposition_sdtm)





## Technologies Used

- R (tidyverse, ggplot2, R Markdown)
- Shiny (dashboards, reactive programming)
