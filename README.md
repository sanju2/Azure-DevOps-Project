# Azure-DevOps-Project
It's a Flask Application & used Docker for build container image. Create Azure DevOps CI/CD pipeline for Azure  App Service. 

#### Create a build pipeline for Azure Container Registry and release pipeline for Azure App Service.

![Architectural Diagram](Architectural%20Diagram2.gif)

### Use following steps.

- Step 1 : Clone this GitHub repository.

![clonerepo](screenshots/1.clonerepo.png)

- Step 2 : Create Container registry.

![createacr](screenshots/2.createacr.png)

- Step 3 : Create Azure DevOps New Project.

![createacr](screenshots/3.createnewproject.png)

- Step 4 : Inside Azure DevOps project create 2 service connections for the Azure container registry & GitHub.

![acr-serviceconnection](screenshots/4.acr-serviceconnection.png)

![github-serviceconnection](screenshots/5.github-serviceconnection.png)

- Step 5 : Create Azure DevOps Build Pipeline.

![create-pipeline1](screenshots/6.create-pipeline1.png)

![create-pipeline2](screenshots/7.create-pipeline2.png)

![create-pipeline3](screenshots/8.create-pipeline3.png)

- Step 6 : After running the build pipeline you can see your build pipeline is a success & the docker image is updated.

![build-pipeline-success](screenshots/9.build-pipeline-success.png)

![repositorycreated](screenshots/10.repositorycreated.png)

- Step 7 : Enable ECR admin access for deployment to Azure App Service.

![enableadminuseracr](screenshots/11.enableadminuseracr.png)

- Step 8 : Create Azure App Service for deploying docker image.

![createappservice1](screenshots/12.createappservice1.png)

![createappservice2](screenshots/13.createappservice2.png)

- Step 9 : Create a release pipeline in Azure DevOps.

![createreleasepipeline](screenshots/14.createreleasepipeline.png)

![createreleasepipeline1](screenshots/15.createreleasepipeline1.png)

![createreleasepipeline2](screenshots/16.createreleasepipeline2.png)

- Step 10 : Deploy 1st release.

![1strelease](screenshots/17.1strelease.png)

- Step 11 : Add port number in Azure App Service.

![Settings5000](screenshots/18.APPServiceApplicationSettings5000.png)

- Step 12 : Finally, Paste the App Service URL in the web browser. You can see the application running.

![webappup&run](screenshots/19.webappup&run.png)

[Learn More Azure DevOps](https://azuredevopslabs.com).

### Thank You! :shipit: