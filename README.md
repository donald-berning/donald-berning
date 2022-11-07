## Patient Centered Management Module (PCMM Web) 
### Product Documentation Repository
The Patient Centered Management Module (PCMM Web) allows users to create, manage, and define teams and assign staff to these teams.  This function helps in maintaining accurate listings for primary care teams and panels.
Detailed information about can be found in  VA System Iventory (**[VASI]**)* Database. 
*NOTE: Right Click on URL above and select 'Open link in new tab' to view VASI information.

### Product Information
- **Product Name:** Patient-Centered Management Module (PCMM)
- **Product Namespace: WEBP
- **Product VASI ID:** [1530]
- **Sub-Product Line:**  1
- **Product Line:**  Clinical Ancillary Product Line (CAP)
- **Portfolio:**  Health Services Portfolio (HSP)

**Product VDD** maintained at: [department-of-veterans-affairs/configuration-management]  
If generating a VDD from within the repository listed above, do the following to create a new VDD issue:
- click the Issues tab, then
- click the green New Issue button, then
- click the New Version Description Document button

### Team Contacts 
Team contacts for **Bar Code Medication Administration (BCMA)** can be found in  VA System Iventory (**[VASI]**)* Database.   
*NOTE: Right Click on URL above and select 'Open link in new tab' to view VASI information.

### Technical Contacts:  
- **Product Owner:** Kim Williams
- **Architect:**
- **Technical Lead:**  First Last
- **Configuration Manager:** Donald (Don) Berning

### Technical SMEs:  
- Naeem Mian
- Cindy Seburn
- Randall Baylis
- Vanessa Herring
- Kirk Fox
- Nancy McGraw
- Ann Chu

### BCMA Product Code Repositories  
This Product has the following code components: **Delphi GUI** and **VistA PSB M** Code.  
Branching strategy is enforced by branch rules.  
- **VistA M Code Repository:** [PSB (VistA) CI] 
- **Delphi GUI Code Repository:** [BCMA GUI CI] 

### Product Lifecycle Management Tool
Only changes justified with a change request (CR) work item number from the associated JIRA project can be made to product code and product documentation artifacts in GitHub repositories. JIRA information listed below:
  - **MAX Group Page:** [VistA-BCMA]
  - **MAX Group Support:** Joshua (Eric) Smith
  - **JIRA Project Page:** [VistA-Bar Code Medication Administration (BCMA)]
  - **JIRA Project Support:** Joshua (Eric) Smith
  - **JIRA Project Key:** VISTAPSB

## Development/SQA Process Map
**THIS SECTION WILL CONTAIN DEVELPOMENT/SQA PROCESS INFORMATION FOR CAP PRODUCTS.  
URLs FOR PROCESS MAP AND PROCESS GUIDE DESCRIBING THE PROCESSES WILL BE LISTED HERE.  
REMOVE THIS TEXT UPON COMPLETION**  
- **Development/SQA Process Map:** [DEV-SQA-PROCESS-MAP] 
- **Development/SQA Process Guide:** [DEV-SQA-PROCESS-GUIDE] 

### Branching strategy
Branching Strategy and Branch Rules to be put in place in coordination with the Sub-Product Line Manager, and if needed, with assistance from the EPMO Configuration Management Department.  

![BCMA Document Branching Strategy Diagram]

### Repository Directory Structure   
The top level folders in the code repository are listed below:
```
CM                    Configuration and Change Management
Design                Analysis, Design and  Business Modeling
Env_Depl_Impl         Environment Docs and Deployment Docs and Implementation Docs
FOIA                  Freedom of Information Act
Other                 Miscellaneous 
PM                    Project Management
Reference             Reference
Released_PDFs         PDFs
Requirement           Requirements
Test                  Test
Third_Party           Manuals, Guides or other assistive documentation
```

*[EPMO Configuration Management Department (CMD) SharePoint site]*

_Notes:_
- _Access to this repository must be coordinated with the Product Line Manager._
- _This **readme.md** file should be updated with information pertinent to product description and activity._
- _To see where certain documents get stored within this standard VA product documentation folder structure, see the [EPMO CMD CM Doc Map]._
- _For standard file naming guidance, see the [EPMO CMD Standard File Naming Convention Guide]._

[//]: # (reference links used in the body of this note - stripped out when the markdown processor does its job.)

 [VASI]: <https://vac21appvem200.va.gov/VASI/#report/def/Definitions_System/report/system_and_application_domain_defs_system_24240>
 [1047]: <https://vac21appvem200.va.gov/VASI/#report/def/Definitions_System/report/system_and_application_domain_defs_system_24240>
 [1530]: <https://vaww.vear.ea.oit.va.gov/#system_and_application_domain_defs_system_23889.htm>
 [department-of-veterans-affairs/configuration-management]: <https://github.com/department-of-veterans-affairs/configuration-management/issues>
 [EPMO Configuration Management Department (CMD) SharePoint site]: <https://dvagov.sharepoint.com/sites/OITEPMOCM/default.aspx>
 [BCMA Product Repository]: <https://github.ec.va.gov/EPMO/vista-bcma-gui-product>
 [PSB (VistA) CI]: <https://github.ec.va.gov/EPMO/vista-psb>
 [BCMA GUI CI]: <https://github.ec.va.gov/EPMO/bcma-gui>
 [DEV-SQA-PROCESS-MAP]: <https://www.processmap.gov>
 [DEV-SQA-PROCESS-GUIDE]: <https://www.processguide.gov>
 [BCMA Document Branching Strategy Diagram]: other/document-branching-strategy.png 
 [VistA-Bar Code Medication Administration (BCMA)]: <https://vajira.max.gov/projects/VISTAPSB/summary>
 [VistA-BCMA]: <https://community.max.gov/display/VAExternal/VistA-BCMA>
 [EPMO CMD CM Doc Map]: <https://dvagov.sharepoint.com/:x:/s/OITEPMOCM/EdBkhxHp681HiHPXU8XhGWYBzUiSPI1nsFLBfEbNQNspbA?e=DFkhwS>
 [EPMO CMD Standard File Naming Convention Guide]: <https://dvagov.sharepoint.com/:w:/s/OITEPMOCM/ETdtPthifJ9CnNWB0VINPCEBOnhHI8G6SH4Lu0aT0uFPNg?e=Z61udO>
   
