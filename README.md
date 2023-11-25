<h1>Project Description</h1>
The project is about automating the deployment process of a web application using Jenkins and its declarative syntax. The pipeline includes stages like building, testing, and deploying to a staging environment. It also includes running acceptance tests and deploying to production if all tests pass.
<br>
1.<h3>Steps:<br></h3>
Go to EC2 console and Create an EC2 instance.<br>
<img width="960" alt="image" src="https://github.com/paulsantosh263/Devops-Project-1/assets/58592054/b4496c0e-0adc-48b9-9308-4b386c9a9ed4">


<br>
<h3>Step 2: Install jenkins and Docker on AWS EC2 Ubuntu instance.<br></h3><br>
Browse instance-public-IP:8080 it will open jenkins dashboard.<br>
Go to Jenkins Dashboard and Click on “New Item”

<br>
<img width="960" alt="image" src="https://github.com/paulsantosh263/Devops-Project-1/assets/58592054/332b8be6-f962-41dc-b8c3-35d07dba9105">

<br>
Give your project a name and select “Pipeline” as the project type.

<br>

<br>
Go to project configuration page

<br>
<img width="960" alt="image" src="https://github.com/paulsantosh263/Devops-Project-1/assets/58592054/4e0ae3d7-efcd-4396-ac0a-b58d2114abd9">

<br>

Now go to the pipeline session, In definition select Pipeline script
<br>
Write a pipeline script<br>
<img width="948" alt="image" src="https://github.com/paulsantosh263/Devops-Project-1/assets/58592054/c5aed7fe-3f39-4040-8f04-e1a052399051">

<br>
Steps:
<br>
Steps blocks consist of the actual operation which needs to be performed inside Jenkins.
<br>
Build the project. You can manually build the project by clicking on the “Build Now” link in the project’s main page

<br>
Build is successfully completed.
<br>
<br>

<br>
<br>
Docker image and container is created using jenkins pipeline.

<br>
<br>
<img width="960" alt="image" src="https://github.com/paulsantosh263/Devops-Project-1/assets/58592054/7ff438f9-201d-4c46-8292-f5b28106af0a">

<br>
<br>
Browse public IP address with port no.8000
<br>
<br>

<img width="960" alt="image" src="https://github.com/paulsantosh263/Devops-Project-1/assets/58592054/7c79989e-9865-4e82-a869-2b5beeb2550d">


<br>


 
