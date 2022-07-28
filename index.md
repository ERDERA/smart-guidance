# Smart Guidance WG

The Smart Guidance aims to ease the FAIRification process by providing tailor-made guidance to the user via an online questionnaire-based tool inspired by the Data Steward Wizard (DSW). This first release works for data stewards of European Reference Network (ERN) Rare Diseases registries who are about to start or are already FAIRifiying their data. The recommendations found in the Smart Guidance are based on technical solutions used, discovered or built in the EJP RD. The advice can be highly technical and points to training sessions or tools that facilitate implementing such solutions. We are working on improving the output template of this tool to be a even more practical FAIRification plan tailored to the user current FAIRification status. 

**Sign up for the Smart Guidance here: https://smartguidance-rd.ds-wizard.org/**

## User guide
The Data stewardship Wizard (DSW) tool was primarily built for data stewards to make a data management plan in collaboration with other team members. The questionnaire style tool is adaptable to other types of questionnaires, which is why we decided to build our Smart Guidance questionnaire in this tool rather than build software from scratch.  
The user guide for the DSW is available [here](https://guide.ds-wizard.org/) for more detailed instructions on the platform itself. 

The first step is to sign up for an account.  We recommend that you use your institutional credentials for your account.  

![sign in pic](https://raw.githubusercontent.com/ejp-rd-vp/smart-guidance/main/screenshotsForUserGuide/1_signup_login.png)

Once you activate your account and log in, you will see the welcome page.

![welcome page pic](https://github.com/ejp-rd-vp/smart-guidance/blob/main/screenshotsForUserGuide/2_new_welcome_page.png)

You can see tabs on the left for Knowledge Models and Projects. A project is created from a knowledge model that is underlying the questionnaire. The Smart Guidance questionnaire is described in the knowledge model titled, **EJP RD Smart Guidance Knowledge Model**. This knowledge model should be used to create a project for Smart Guidance.
### Create and work on a project
*First time user:*  
Click on Projects, in the first time you will see that there are no projects.  
Click on ‘Create’ and select the ‘Custom’ tab instead of the ‘From Template’ tab.  
Give your project a name.  
Then select a knowledge model from which your project will be built. Be sure to use the **EJP RD Smart Guidance Knowledge Model 1.0.0** to create a new project. And hit save.

![create project pic](https://raw.githubusercontent.com/ejp-rd-vp/smart-guidance/main/screenshotsForUserGuide/3_create_and_custom_project.png)

The project will open up showing the various chapters and the questions in them.

![open project pic](https://raw.githubusercontent.com/ejp-rd-vp/smart-guidance/main/screenshotsForUserGuide/4_smartguidance-rd.ds-wizard.org_projects_test_open.png)

*Repeat user*

Once you sign in you only must click on the projects tab and start working on your specific project

### Smart Guidance questionnaire 
We have seven chapters covering the various areas of FAIRification of a resource. Once answered, the questions turn green from red. Some answers will trigger more questions. 
1. Administrative information
    * This chapter deals with information related to the pre-FAIRification process, such as the goals, the anticipated timeline and allocated budget for FAIRification.
    * This chapter also addresses questions related to ERDRI.dor and the composition of your team members (stakeholders).
2. Re-using data
    * This chapter is about FAIRification options for pre-existing data or metadata that was collected before the FAIRification process began.
    * When data is not made FAIR at the time of data collection / data entry, it should be made FAIR retrospectively. For doing so, you would follow a slightly different FAIRification process than when making data FAIR 'at the source'.
    * This workflow for retrospective FAIRification is described in this [manuscript](https://doi.org/10.1162/dint_a_00028).
3.	Creating and collecting data
    * This chapter covers ways of creating and collecting data in a FAIR way focusing on how to use your electronic data capture system to make you data FAIR as you collect it.
    * For example, if you collect data through electronic case report forms, you should execute most FAIRification steps before starting the actual data collection. That way, data can be transformed into machine-readable, FAIR data, in real-time when the data is collected. 
    * More information can be found in the following manuscripts: [here](https://ojrd.biomedcentral.com/articles/10.1186/s13023-021-02004-y) and [here](https://pubmed.ncbi.nlm.nih.gov/34454078/).
4.	Processing data
    * This chapter covers the processing of data as it is being collected. It covers the different pseudonymisation tools that could be used for registry data.
5.	Interpreting data
    * This chapter deals with the modelling of your data, so it can be annotated with unambiguous terms and the different ways it can be queried.
6.	Describing data
    * This chapter deals with the information needed to properly describe your data, so users can reuse it. It covers the use of FAIR Data Points and database technologies to store data.
7.	Giving access to data
    * This chapter deals with the information needed by people who will re-use your data, and with the access conditions they will need to follow.    

### Work on the project

Click on ‘Projects’ on the left menu and open the project that was already created.

Several collaborators can work on a project together and can leave comments and TO DOs on the questionnaire that are visible to other users. The project can be cloned to have another copy of the answered questionnaire. 

![work on project pic](https://raw.githubusercontent.com/ejp-rd-vp/smart-guidance/main/screenshotsForUserGuide/5_question_overview.png)

More detailed information is in the DSW User Guide, relevant sections are:

[Open Project](https://guide.ds-wizard.org/for-users/for-researchers/projects-dmps/open-project)  
[Share Project](https://guide.ds-wizard.org/for-users/for-researchers/projects-dmps/share-project)  
[Comments on the project](https://guide.ds-wizard.org/for-users/for-researchers/projects-dmps/comments)  
[Clone Project](https://guide.ds-wizard.org/for-users/for-researchers/projects-dmps/clone-project)  

### Get output
The given answers can be obtained as an output of the questionnaire in forms of a "document'. This can be done in the "Document" menu (see instructions below). It is highly recommended to use an existing template to generate your report. 

![outut pic](https://raw.githubusercontent.com/ejp-rd-vp/smart-guidance/main/screenshotsForUserGuide/6_create_report.png)
