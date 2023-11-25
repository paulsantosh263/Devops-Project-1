<h1>Project Description</h1>
The project is about automating the deployment process of a web application using Jenkins and its declarative syntax. The pipeline includes stages like building, testing, and deploying to a staging environment. It also includes running acceptance tests and deploying to production if all tests pass.
<br>
1.<h3>Steps:<br></h3>
Go to EC2 console and Create an EC2 instance.<br>
<img width="960" alt="image" src="https://github.com/paulsantosh263/Automating-Web-App-Deployment-with-Jenkins-Declarative-Pipeline./assets/58592054/596e007e-cd91-4869-983a-aac44ca3889c">

<br>
<h3>Step 2: Install jenkins and Docker on AWS EC2 Ubuntu instance.<br></h3><br>
Browse instance-public-IP:8080 it will open jenkins dashboard.<br>
Go to Jenkins Dashboard and Click on “New Item”

<br>
<img width="960" alt="image" src="https://github.com/paulsantosh263/Automating-Web-App-Deployment-with-Jenkins-Declarative-Pipeline./assets/58592054/0f1c6398-eca5-48cd-83cb-c7239faca236">
<br>
Give your project a name and select “Pipeline” as the project type.

<br>
<img width="958" alt="image" src="https://github.com/paulsantosh263/Automating-Web-App-Deployment-with-Jenkins-Declarative-Pipeline./assets/58592054/c076ccb0-4f1f-4e72-8ecd-9c85b00f9ae7">
<br>
Go to project configuration page

<br>
<img width="960" alt="image" src="https://github.com/paulsantosh263/Automating-Web-App-Deployment-with-Jenkins-Declarative-Pipeline./assets/58592054/a85885fe-ccd6-4f8f-a68e-b256fbfe4f0d">
<br>

Now go to the pipeline session, In definition select Pipeline script
<br>
Write a pipeline script<br>
<img width="960" alt="image" src="https://github.com/paulsantosh263/Automating-Web-App-Deployment-with-Jenkins-Declarative-Pipeline./assets/58592054/cac7c05c-77dc-4e08-9a9f-6910367e3fd4">
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
<img width="960" alt="image" src="https://github.com/paulsantosh263/Automating-Web-App-Deployment-with-Jenkins-Declarative-Pipeline./assets/58592054/93f6c436-7dfb-4d39-abff-3edbf1619750">
<br>
<br>
Docker image and container is created using jenkins pipeline.

<br>
<br>
<img width="512" alt="image" src="https://github.com/paulsantosh263/Automating-Web-App-Deployment-with-Jenkins-Declarative-Pipeline./assets/58592054/bb5d3bf0-9411-471c-beaf-76059a62ec19">
<br>
<br>
Browse public IP address with port no.8000
<br>
<br>

<img width="960" alt="image" src="https://github.com/paulsantosh263/Automating-Web-App-Deployment-with-Jenkins-Declarative-Pipeline./assets/58592054/79727bf5-1298-476c-91e2-bd877ce1de6a">


<br>


 
