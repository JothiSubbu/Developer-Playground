<html>
<style>
.boxed 
{
  border: 1px solid blue ;
}
</style>
<style>
.btn {
  border: 2px solid gray;
  background-color: #202020;
  color: white;
  padding: 10px 15px;
  font-size: 16px;
  cursor: pointer;
}
.info {
  border-color: gray;
  color: gray;
  
}
<style>
html,div,body{
    background-color:#1a1a1a;
    font-family: 'IBM Plex Sans', sans-serif;
}

.content p{
  font-family: 'IBM Plex Sans', sans-serif;  
  font:15px;
  color: #fff;
}
pre{
    background-color:#d9dbde;
    color:#000;
    font-family: 'IBM Plex Sans', sans-serif;
    font:12px;
}
.content h4{
    color:#fff;
}
.content h6{
    font-family: 'IBM Plex Sans', sans-serif;
    background-color:#1a1a1a;
    color:#fff;
}
.content h3{
    font-family: 'IBM Plex Sans', sans-serif;
    color: #2a67f5;
    background-color:#1a1a1a;
}
.h3{
    font-family: 'IBM Plex Sans', sans-serif;
    color: #2a67f5;
    background-color:#1a1a1a;
}
ul, ol,b{ 
    font-family: 'IBM Plex Sans', sans-serif;
    color: #fff;
}
#ul1{
  font-family: 'IBM Plex Sans', sans-serif;
    color: #fff;
}
.button.is-dark.is-medium {
  font-family: 'IBM Plex Sans', sans-serif;
  background-color: #1a1a1a;
  border-color: white;
  color: #fff;
}
.button.is-dark.is-medium:hover {
  font-family: 'IBM Plex Sans', sans-serif;
  background-color: #2a67f5;
  border-color: white;
  color: #fff;
}
.title.is-3{
  font-family: 'IBM Plex Sans', sans-serif;
  color:#fff;
}
.subtitle.is-4{
    font-family: 'IBM Plex Sans', sans-serif;
    color:#fff;
}
​
</style>
<body style="font-family: 'IBM Plex Sans', sans-serif;background-color:#1a1a1a;">
<div style="font-family: 'IBM Plex Sans', sans-serif;background-color:#1a1a1a;">
​
</style>
​
<body>

<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/unnamed.jpg" width = "500" height= "500">


<h2 class="title is-3 ">Cloud Pak Sample App</h2>

<p> This sample app aims to showcase the functionalities available on the Cloud Pak platform, with regards to Cloud Pak for Data and Cloud Pak for Integration
</p>

<h3> Getting Started</h3></span>

<span style="color:grey"><h2>1. Create an account on IBM's Cloud Platform</h2></span>

To ensure a completely immersive experience with Cloud Pak services, create an account on IBM's cloud platform.

<a class="button is-dark is-medium" title="Log in here" href="https://dataplatform.cloud.ibm.com/login?context=cpdaas">Log in here</a>
<br/>

 

<span style="color:grey"><h2> 2. Check prerequisites linked to Cloud account</h2></span>

<p> This sample app requires the user to avail certain instances present in the Services catalog. The instances are listed below:</p>


<h5>2.1 Event Streams</h5>
<p>Built on Apache Kafka, IBM Event Streams which is a part of IBM's Cloud Pak for integration is a high-throughput, fault-tolerant, event streaming platform that helps you build intelligent, responsive, event-driven applications.</p>

<h6>Follow the below steps to create an event stream instance and connect your application data to event streams.</h6>

<p>Step1: Click the below button to create event stream instance.</p>
<a class="button is-dark is-medium" title="Event Streams" href="https://cloud.ibm.com/catalog/services/event-streams">Event Streams</a><br><br>
<p>Step 2 : After creating the instance you will be re-directed to a page as shown below.Select topic and click on create topic
 </p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/Step1.jpg" width = "750" height= "750">
<p>Step 3 : Give your topic an appropriate name and click next. Make sure to remember the topic name as it will be used in step 6.</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step2-kafka.jpg" width = "750" height= "750">

<p>Step 4 :Select the number of partitions and click next</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step3-kafka.jpg" width = "750" height= "750">

<p>Step 5 : Choose message retention as per requirement and click on create topic.</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step4-kafka.jpg" width = "750" height= "750">
<p>Step 6 : Now u can see the topic that you have created under the topics section.Now select service credentials section and click on new credentials.Give the credentials a name and select the role as manager. Once the credentials are created you can view it in the table. Expand the table row and make note of <b>apikey</b>,<b>kafka_brokers_sasl</b></p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step5-kafka.jpg" width = "750" height= "750">

<h5>2.2 Waston Machine Learning </h5>
<p>IBM Watson Machine Learning helps data scientists and developers accelerate AI and machine learning deployment on IBM Cloud Pak for Data.With watson machine learning you can deploy AI models at scale across any cloud on an open.</p>
<a class="button is-dark is-medium" title="Machine Learning" href="https://dataplatform.cloud.ibm.com/data/catalog/pm-20?context=cpdaas&target=services">Machine Learning</a><br><br>
<p>Clicking on the button will open up a page in the browser as shown below. After choosing the light plan, give the instance a name and click on the <b>create</b> button on the right panel.</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/bd2e464b160ce4751ec84fe1593c37a367206553/didact/images/machineLearning-instance.png" width = "750" height= "750">


<h5>2.3 Mongo DB database </h5>
<a class="button is-dark is-medium" title="Databases for MongoDB" href="https://dataplatform.cloud.ibm.com/data/catalog/databases-for-mongodb?context=cpdaas&target=services">Databases for MongoDB</a><br>
<p>Clicking on the button will open up a page in the browser as shown below. Give the instance a name and  click on the <b>create</b> button on the right panel.</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/bd2e464b160ce4751ec84fe1593c37a367206553/didact/images/Mongo-instance.png" width = "750" height= "750">


</body>


<span style="color:grey"><h2>3. Clone the GitHub repo for this Sample App</h2></span>

<p>This Sample app needs to be cloned onto the Developer playground.</p>

<a class="button is-dark is-medium" title="Get the code" href="didact://?commandId=vscode.didact.sendNamedTerminalAString&text=nodejs$$git+clone+https://github.ibm.com/SUMANVITA-K/LoanApp-CP">Get the code</a><br>

<span style="color:grey"><h2>4.Deploy AutoAI Model</h2></span>

<p>To deploy the autoAI model to deployment space the program will ask for API key and space id</p>
<ul><h6>4.1 Steps to generate API Key</h6>
<li>
<p>Step 1 : Go to <a href="https://cloud.ibm.com/">IBM cloud</a> and login with your mail id. click on the Manage tab and select Access (IAM), the cloud Identity and Access Management page will be displayed.
 </p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/Step1.jpg" width = "750" height= "750">
</li>
<li>
<p>Step 2 :  Click on API keys on the left panel.</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step2.jpg" width = "750" height= "750">
</li>
<li><p>Step 3 : In API keys, click on Create an IBM Cloud API key and give a Name and Description Accordingly as shown</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step3.jpg" width = "750" height= "750">
</li>
<li>
<p>Step 4 : Once the API key is generated Successfully, copy the API Key as store it so that it can be used while deploying the model.</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step4.jpg" width = "750" height= "750">
</li>
</ul>

<ul><h6>4.2 Steps to generate deployment space</h6>
<li>
<p>Step 1 : Go to <a href="https://dataplatform.cloud.ibm.com/">IBM CloudPak for data</a> and login with your mail id. Once you login click on view all spaces button as shown in the figure below.
 </p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step1-spaceId.png" width = "750" height= "750">
</li>
<li>
<p>Step 2 :  Click on create deployment space.</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step2-spaceId.png" width = "750" height= "750">
</li>
<li><p>Step 3 : Give the deployment a name and add a machine learning instance created in step2.2 .Click on create button after filling the details.</p>
<img src = "https://github.com/IBM/Developer-Playground/raw/4be4c6c9dd9cc9164a7447b07b4c54e7daca9a97/didact/images/step3-spaceID.png" width = "750" height= "750">
</li>
<li>
<p>Step 4 : Click on view deployement space and then select manage tab.Under this tab, copy the space GUID.</p>

</li>
</ul>

<a class="button is-dark is-medium" title="Build the App" href="didact://?commandId=terminal-for-python-nodejs-container:new">Open Python Terminal</a><br>

<p>Clicking on this button will first install all the libraries required to run the python based ML model. After the installation is complete you would be asked to enter the API Key and space Id that you have generated from steps 4.1 and 4.2</p>
<a class="button is-dark is-medium" title="Build the App" href="didact://?commandId=vscode.didact.sendNamedTerminalAString&text=python-nodejs%20terminal%203$$cd%20${CHE_PROJECTS_ROOT}/LoanApp-CP;alias%20python='/usr/local/bin/python3.8';python3.8%20-m%20pip%20install%20-r%20requirements.txt;python3.8%20DeployModel/DeployMLModel.py">Deploy Model</a><br>


<span style="color:grey"><h2>5. Build the App</h2></span>

<p> Build the application to explore it's functionalities within the given terminal.</p>
<a class="button is-dark is-medium" title="Build the App" href="didact://?commandId=vscode.didact.sendNamedTerminalAString&text=python-nodejs%20terminal%203$$cd%20${CHE_PROJECTS_ROOT}/LoanApp-CP;npm%20install">Build the App</a><br>

<span style="color:grey"><h4>6.Adding credentials to the App</h4></span>


<p>Add the sasl password value,broker list and topic name collected from the above steps in the .env file </p>

<a class="button is-dark is-medium" title="Edit environment variables" href="didact://?commandId=vscode.open&projectFilePath=LoanApp-CP/.env">Edit environment variables</a><br>

<span style="color:grey"><h2>7.Launch the Application</h2></span>

<p>Upon launching the app,the application will start running. </p>

<a class="button is-dark is-medium" title="Launch the Application" href="didact://?commandId=vscode.didact.sendNamedTerminalAString&text=python-nodejs%20terminal%203$$npm+start">Launch the Application</a><br>


<!-- <span style="color:grey"><h2>7. Explore the Code.</h2></span>

<a class="button is-dark is-medium" title="Explore the Code" href="didact://?commandId=workbench.view.explorer">Explore the Code</a><br><br>

<p> -->

<span style="color:grey"><h2>8.Delete Deployment</h2></span>

<p>Before deleting the deployment,make sure to stop the application</p>

<a class="button is-dark is-medium" title="Stop the application" href="didact://?commandId=vscode.didact.sendNamedTerminalCtrlC&text=python-nodejs%20terminal%203">Stop Application</a><br>

<p>Deleting deployment will help you save Capacity Unit Hours(CUH).</p>

<a class="button is-dark is-medium" title="Delete deployment" href="didact://?commandId=vscode.didact.sendNamedTerminalAString&text=python-nodejs%20terminal%203$$python3.8%20DeleteDeploy/deleteDeploy.py">Delete deployment</a><br>
