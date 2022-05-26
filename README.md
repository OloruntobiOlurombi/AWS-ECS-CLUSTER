# Topic: AWS-ECS-CLUSTER

### Overview
> Amazon Elastic Container Service (Amazon ECS) is a highly scalable and fast container management service. You can use it to run, stop, and manage containers on a cluster. With Amazon ECS, your containers are defined in a task definition that you use to run an individual task or task within a service. In this context, a service is a configuration that you can use to run and maintain a specified number of tasks simultaneously in a cluster. You can run your tasks and services on a serverless infrastructure that's managed by AWS Fargate. Alternatively, for more control over your infrastructure, you can run your tasks and services on a cluster of Amazon EC2 instances that you manage, [see more](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html).


### Prerequisites: 
> AWS Account

### Steps to create a Cluster in ECS

#### Step 1
> Navigate to the ECS dashboard, and select the Clusters service from the left-hand side menu pane.

![image](https://user-images.githubusercontent.com/40290711/170455488-0efbe374-3fca-4116-8e24-205ef53cb287.png)

![image](https://user-images.githubusercontent.com/40290711/170455716-9b0311d6-722a-4b93-9640-6f2c194a8142.png)

### Step 2
> On the Clusters page, choose the Create cluster button.

![image](https://user-images.githubusercontent.com/40290711/170456101-8679ca00-ebd8-4def-aef9-d47fedc30892.png)

### Step 3
> At the Select cluster template step, choose the Networking only compatibility

![image](https://user-images.githubusercontent.com/40290711/170457537-a7eac307-7c31-4063-befc-79218cfa2cb3.png)

> Choosing the Networking only template, that allows creating a cluster and optionally create a VPC, and subnets.
