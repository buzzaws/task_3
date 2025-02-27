### Task 3: Deploy Docker Application on AWS EC2
#### Objective: Run the Docker container on the Terraform-created EC2 instance. 
steps)
i)SSH into the EC2 instance.

ssh -i Assign.pem ubuntu@34.230.4.107

ii)Install Docker and pull the Docker image from Docker Hub or AWS ECR.

docker pull buzzeraws/assignment:latest

iii) Run the containerized application

docker run -d buzzeraws/assignment:latest

iv) Verify application deployment by accessing the public IP in a web browser.

34.230.4.107:8000

####### Snapshot ##########

<img width="1200" alt="Screenshot 2025-02-28 at 12 43 59 AM" src="https://github.com/user-attachments/assets/4ab66178-2e0a-4ae6-abf5-eecfc5911655" />


<img width="1200" alt="Screenshot 2025-02-27 at 11 51 08 PM" src="https://github.com/user-attachments/assets/1833ae05-e844-4f28-b4ab-e60b9be388ee" />


