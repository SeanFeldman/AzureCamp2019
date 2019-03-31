# Azure Camp 2019

This is the code for the Global Azure camp 2019 in Calgary, Alberta. The theme of this camp is around containers and Kubernetes. For good measure we're adding a little bit of AI into the mix to reflext the current technology trend.

Our application is an application form for a job posting site. We're going to allow people to post jobs on the site and then we'll display them for others to apply. This system is built on top of a cluster of microservices, to demonstrate a common pattern used these days.

If you're considering building a system on microservices it is recommended to invest into a research up front and have a clear understanding of what the advantages and disadvantages of microservices are. https://dwmkerr.com/the-death-of-microservice-madness-in-2018/ is a pretty good article to get you started. 

## Services

1. Salary prediction service - AI based service that will rate your offered salary against the industry average for your province. 
1. UI - the visual front end for the application. Simple web application with a couple of forms. 
1. Model builder - project to build the AI model for the salary prediction service.
