<h1>How To deploy a simple flask app on azure</h1>
<p>In this project we will learn to deploy a simple flask app on azure portal. Here I have given all the required links to microsoft offical documentation. You can follow the steps as per my guidance. Please note that use the code given in this repository if you face any difficulties you can contact me.</p>
<p>Azure gives us multiple ways to deploy and manage applications on cloud.
Cloud is not all about application deployment but it has wide range of services to manage storage, scale resources, develop a data engineering architecture for data analysis and much more</p>
<p>
<h2> Following are the ways by which we can deploy a flask app on azure </h2>
<ol>
<li>Using Azure App Services:<br>
<p>Azure App Service is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. You can develop in your favorite language, be it .NET, .NET Core, Java, Ruby, Node.js, PHP, or Python. Applications run and scale with ease on both Windows and Linux-based environments.

App Service not only adds the power of Microsoft Azure to your application, such as security, load balancing, autoscaling, and automated management. You can also take advantage of its DevOps capabilities, such as continuous deployment from Azure DevOps, GitHub, Docker Hub, and other sources, package management, staging environments, custom domain, and TLS/SSL certificates.

With App Service, you pay for the Azure compute resources you use. The compute resources you use are determined by the App Service plan that you run your apps on. For more information, see Azure App Service plans overview.</p>
refer https://learn.microsoft.com/en-us/azure/app-service/overview for more information.

To deploy a flask app without database you can follow the  documentation mentioned below<br>
https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-cli%2Cvscode-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli

</li>
<li>Using Azure Virtual Machine:<br>
<p>If your web hosting requirements aren't directly supported by the Azure Web app platform, you can leverage virtual machines to customize and control every aspect of the web server. Learn how to create, configure, and manage virtual machines on Linux and Windows that host web apps. This learning path can help you prepare for the Microsoft Certified: Azure Developer Associate certification.</p>

refer https://learn.microsoft.com/en-us/training/paths/deploy-a-website-with-azure-virtual-machines/ to deploy your app on virtual machines.
You can also follow https://www.geeksforgeeks.org/hosting-a-web-application-on-microsoft-azure-in-iaas/ to host app on az vm.

Advantages of Azure VM 
By using azure app service you are deploying your app as platform as a service method. But if you deploy it on a virtual machine it as Infrastructure as a service. Both have their own advantages for example app service manages memory, softwares like OS and other system softwares, computing and processing power, storage and many other things yet we can scale these resourses as per our need. But Azure VM gives a complete access to OS and other administrative stuffs. Now it is our responsiblity to look after all the services needed to run our app. Some of the advantages are listed below.
<ol>
<li>Scalability: As the demand increases, the system capacity can be increased accordingly. Therefore, scalability is a major advantage here.</li>
<li>Storage: Users can share various storage options like private storage, public storage or both based on the sensitivity of the data.</li>
<li>Customization of Controls: Enterprises can customize the control options based on the sensitivity and volume of the data.</li>
<li>Tools: Users and developers can use prebuilt out-of-the-box tools, that will not only optimize the process but also save a lot of time.</li>
<li>Security: This system comes with various encryption options along with customizable measures to increase the security of the data.</li>
<li>Accessibility: Accessible from any internet-connected device.</li>
<li>Speedy Market Introduction: Using Azure results in the fast market introduction of services and platforms due to out-of-the-box provisions.</li>
<li>Regular Updates: Regular system upgrades is a major advantage of Azure with respect to the legacy system.</li>
</ol>

</li>
<ol>
</p>
