# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I decided to go choose a web app and not a VM. The app in question is a simple CMS-article system that stores text data and images, so definitely a lightweight app. At this point I don't expect much traffic, and it is not expected that extreme horizontal or vertical scalability is needed (even though a web app would also be able to handle that). The availability of a web app is also more than enough for this project. 
Given these framework conditions, it is not necessary at this point in time, to have control over the operating system (IaaS). A web app, a PaaS Service, is more than sufficient to handle the application, and at much lower costs. The HW limitations - a maximum of 14GB of memory and 4 vCPU cores - are absolutely no issue right now. 


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If there would be a significant upscale in the usage that would require a major HW upgrade beyond the 14GB memory / 4 vCPU cores, or if the workflow would change and include any tailor made parts, for example a tailor made emailing and notification system, a switch to VM may be necessary. 
