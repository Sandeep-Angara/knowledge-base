# Power Platform ALM

With App Life Cycle Management, you can eaily manage solutions between different environments, say it Development, Testing, and Production. To automate ALM process, we have pipelines in Azue DevOps. With that we can build pipelines that extracts solution from one environment, track changes in repository and finally moves solution to target environments (Test / Production). For setting up pipelines and to implement ALM, we need to perform different configurations and setup. 

Here is a checklist in the order of operations
- [x] Azure DevOps- Setting up Organization, Project, Repository, Configure permission and Installing Build Tools
- [x] Azure App registration
- [x] Service Connections 
- [x] Extract / Build Pipeline
- [x] Release Pipeline
- [x] Deployement Settings File
- [x] CI/CD Trigger 

### Setting up Azure DevOps

1. Open up dev.azure.com
2. Create organization
3. Create a project 
4. After creating a project, you will see a left navigation with all tools
5. Go to Repos, hit on initialize button n your default repository or create a new by clicking on repository name on top navigation
6. Now, to configure required permissions got to project settings which you will find in your left-bottom
7. Head to Repositories and click on Security tab
8. For Project Collection Build Service Accounts, give contribute access and do the same for users (<YourProjectName> Build Service)as well
9. Upnext, we need Power Platform Build Tools.To install, head to marketplace by clicking the shopping icon on top navigation
10. Search for Power Platform Build Tools and Install

  
  
 
