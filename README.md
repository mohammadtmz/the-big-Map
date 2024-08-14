# The Big Map of My GitHub Repositories

Welcome to my GitHub profile! This README serves as a roadmap of my repositories, detailing the organization and content across different areas of expertise including Foundations, Cloud, DevOps, Data Science, Projects, and Resources.

## Repository Structure Overview

### 1. [Foundation](https://github.com/mohammadtmz/Foundation)
This repository contains the foundational knowledge and tools essential for a Cloud Engineer and DevOps Engineer.

- **01_Linux/**
  - `README.md`: Overview and learning resources for Linux fundamentals.
  - `Commands.md`: Common Linux commands and scripts.
  - **Tutorials/**
    - `Basic_Commands.md`: Tutorial on basic Linux commands.
    - `Shell_Scripting.md`: Shell scripting tutorial.
    - `Advanced_Topics.md`: Advanced Linux topics.
  - **Cheat_Sheets/**
    - `Bash_Cheat_Sheet.md`: Quick reference guide for Bash commands.
    - `Vim_Cheat_Sheet.md`: Cheat sheet for the Vim editor.

- **02_Networking/**
  - `README.md`: Overview and learning resources for networking concepts.
  - `Basics.md`: Networking basics including TCP/IP and subnetting.
  - **Tutorials/**
    - `TCP_IP.md`: Detailed explanation of the TCP/IP model and protocols.
    - `Subnetting.md`: Guide on IP subnetting.
    - `Network_Security.md`: Basics of network security.
  - **Tools/**
    - `Wireshark.md`: Guide on using Wireshark for network analysis.
    - `Netcat.md`: Usage guide for Netcat tool.

- **03_Scripting/**
  - `README.md`: Overview and resources for scripting languages.
  - **Bash_Scripts/**
    - `Script1.sh`: Example Bash script.
    - `Script2.sh`: Another example Bash script.
  - **Python_Scripts/**
    - `Script1.py`: Example Python script.
    - `Script2.py`: Another example Python script.
  - **Tutorials/**
    - `Bash_Tutorial.md`: Hands-on tutorial for Bash scripting.
    - `Python_Tutorial.md`: Hands-on tutorial for Python scripting.

- **04_Git_and_Version_Control/**
  - `README.md`: Overview and learning resources for Git and version control.
  - `Git_Basics.md`: Basics of Git.
  - **Tutorials/**
    - `Git_Workflow.md`: Guide on Git workflow and best practices.
    - `Branching.md`: Git branching strategies.
  - **Tools/**
    - `Git_Aliases.md`: Useful Git command aliases.
    - `Git_GUIs.md`: Overview of Git GUI tools.

- **05_Mathematics_and_Statistics/**
  - `README.md`: Core mathematical concepts and statistics.
  - `Linear_Algebra.md`: Basics of linear algebra.
  - `Probability.md`: Introduction to probability and statistics.
  - **Tutorials/**
    - `Linear_Algebra_Exercises.md`: Exercises for linear algebra.
    - `Probability_Exercises.md`: Problem sets for probability.

### 2. [Cloud](https://github.com/mohammadtmz/Cloud)
This repository covers various cloud technologies, including AWS, Azure, and GCP, along with Terraform scripts and tutorials.

- **01_AWS/**
  - **Services/**
    - **EC2/**
      - `README.md`: Overview of EC2 service.
      - `Launch_Instances.md`: Guide on launching EC2 instances.
      - `IAM_Roles.md`: Using IAM roles with EC2.
    - **S3/**
      - `README.md`: Overview of S3 service.
      - `Bucket_Management.md`: Guide on managing S3 buckets.
      - `Security_Best_Practices.md`: S3 security best practices.
    - **IAM/**
      - `README.md`: Overview of IAM service.
      - `Policies.md`: Creating and managing IAM policies.
      - `Users_and_Roles.md`: Managing IAM users and roles.
  - **Terraform_Scripts/**
    - `VPC_Terraform.tf`: Terraform script for setting up a VPC.
    - `EC2_Terraform.tf`: Terraform script for launching EC2 instances.
    - `S3_Terraform.tf`: Terraform script for S3 bucket setup.
  - **Tutorials/**
    - `Basic_AWS_Setup.md`: Setting up an AWS environment.
    - `Using_Lambda.md`: Tutorial on AWS Lambda.
    - `Deploying_Web_Apps.md`: Deploying web applications on AWS.

- **02_Azure/**
  - **Services/**
    - **VM/**
      - `README.md`: Overview of Azure Virtual Machines.
      - `VM_Deployment.md`: Guide on deploying VMs in Azure.
      - `Security_Best_Practices.md`: VM security best practices.
    - **Storage/**
      - `README.md`: Overview of Azure Storage.
      - `Blob_Storage.md`: Working with Azure Blob Storage.
      - `Access_Control.md`: Managing access to storage resources.
    - **Azure_AD/**
      - `README.md`: Overview of Azure Active Directory.
      - `User_Management.md`: Managing users in Azure AD.
      - `Integrating_Azure_AD.md`: Integrating Azure AD with applications.
  - **Terraform_Scripts/**
    - `VM_Terraform.tf`: Terraform script for deploying Azure VMs.
    - `Storage_Terraform.tf`: Terraform script for Azure Storage.
    - `Network_Terraform.tf`: Terraform script for Azure Networking.
  - **Tutorials/**
    - `Azure_Basics.md`: Getting started with Azure.
    - `Deploying_Containers.md`: Deploying containers in Azure.
    - `Using_Azure_Functions.md`: Tutorial on Azure Functions.

- **03_GCP/**
  - **Services/**
    - **Compute_Engine/**
      - `README.md`: Overview of Compute Engine.
      - `Instance_Management.md`: Managing instances in Compute Engine.
      - `Networking.md`: Configuring networking for instances.
    - **Cloud_Storage/**
      - `README.md`: Overview of Cloud Storage.
      - `Bucket_Setup.md`: Setting up buckets in Cloud Storage.
      - `Security.md`: Security best practices for Cloud Storage.
    - **IAM/**
      - `README.md`: Overview of IAM in GCP.
      - `Roles_and_Permissions.md`: Managing roles and permissions.
      - `Service_Accounts.md`: Using service accounts in GCP.
  - **Terraform_Scripts/**
    - `Compute_Terraform.tf`: Terraform script for Compute Engine.
    - `Storage_Terraform.tf`: Terraform script for Cloud Storage.
    - `Networking_Terraform.tf`: Terraform script for networking in GCP.
  - **Tutorials/**
    - `GCP_Basics.md`: Getting started with GCP.
    - `Deploying_VM.md`: Deploying virtual machines on GCP.
    - `Using_BigQuery.md`: Tutorial on using BigQuery in GCP.

### 3. [DevOps](https://github.com/mohammadtmz/DevOps)
This repository includes DevOps tools and practices such as CI/CD pipelines, Infrastructure as Code, containerization, and monitoring and logging.

- **01_CI_CD/**
  - **Jenkins/**
    - `README.md`: Overview of Jenkins.
    - **Pipeline_Examples/**
      - `CI_Pipeline.groovy`: CI pipeline example.
      - `CD_Pipeline.groovy`: CD pipeline example.
    - `Jenkinsfile`: Example Jenkinsfile for a project.
  - **GitLab_CI/**
    - `README.md`: Overview of GitLab CI.
    - **Pipeline_Examples/**
      - `CI_Pipeline.yml`: CI pipeline example.
      - `CD_Pipeline.yml`: CD pipeline example.
    - `.gitlab-ci.yml`: Example GitLab CI configuration file.
  - **GitHub_Actions/**
    - `README.md`: Overview of GitHub Actions.
    - **Workflow_Examples/**
      - `CI_Workflow.yml`: CI workflow example.
      - `CD_Workflow.yml`: CD workflow example.
    - `action.yml`: Example GitHub Action configuration file.
  - **Tutorials/**
    - `Jenkins_Tutorial.md`: Jenkins pipeline tutorial.
    - `GitLab_CI_Tutorial.md`: GitLab CI/CD tutorial.
    - `GitHub_Actions_Tutorial.md`: GitHub Actions tutorial.

- **02_Infrastructure_as_Code/**
  - **Terraform/**
    - **AWS_Terraform/**
      - `VPC_Setup.tf`: Terraform script for setting up a VPC in AWS.
      - `EC2_Setup.tf`: Terraform script for launching EC2 instances.
      - `S3_Setup.tf`: Terraform script for setting up S3 buckets.
    - **Azure_Terraform/**
      - `VM_Setup.tf`: Terraform script for setting up VMs in Azure.
      - `Storage_Setup.tf`: Terraform script for Azure Storage.
      - `Network_Setup.tf`: Terraform script for Azure networking.
    - **GCP_Terraform/**
      - `Compute_Setup.tf`: Terraform script for Compute Engine in GCP.
      - `Storage_Setup.tf`: Terraform script for Cloud Storage in GCP.
    - **Modules/**
      - `VPC_Module.tf`: Reusable module for setting up a VPC.
      - `EC2_Module.tf`: Reusable module for setting up EC2 instances.
  - **Ansible/**
    - **Playbooks/**
      - `Web_Server_Setup.yml`: Playbook for setting up a web server.
      - `DB_Server_Setup.yml`: Playbook for setting up a database server.
      - `Security_Setup.yml`: Playbook for configuring server security.
    - **Roles/**
      - **Web_Server/**
        - `tasks/main.yml`: Main tasks for the role.
        - `handlers/main.yml`: Handlers for the role.
        - `templates/`: Templates for the role.
        - `files/`: Files for the role.
      - **DB_Server/**
        - `tasks/main.yml`: Main tasks for the role.
        - `handlers/main.yml`: Handlers for the role.
        - `templates/`: Templates for the role.
        - `files/`: Files for the role.
    - **Inventories/**
      - **dev/**
        - `hosts`: Hosts file for development environment.
        - `group_vars/`: Group variables for development.
      - **prod/**
        - `hosts`: Hosts file for production environment.
        - `group_vars/`: Group variables for production.
  - **Tutorials/**
    - `Terraform_Tutorial.md`: Terraform tutorial.
    - `Ansible_Tutorial.md`: Ansible tutorial.
    - `IaC_Best_Practices.md`: Best practices for Infrastructure as Code.

- **03_Containerization/**
  - **Docker/**
    - **Dockerfiles/**
      - `Dockerfile_Web_App`: Dockerfile for a web application.
      - `Dockerfile_DB`: Dockerfile for a database.
    - **Compose_Files/**
      - `docker-compose.yml`: Compose file for a multi-container app.
      - `docker-compose.override.yml`: Override file for custom configurations.
    - **Tutorials/**
      - `Docker_Basics.md`: Getting started with Docker.
      - `Docker_Networking.md`: Networking in Docker.
      - `Docker_Volumes.md`: Working with Docker volumes.
    - **Cheat_Sheets/**
      - `Docker_Cheat_Sheet.md`: Quick reference guide for Docker commands.
  - **Kubernetes/**
    - **Manifests/**
      - `Deployment.yaml`: Example deployment manifest.
      - `Service.yaml`: Example service manifest.
      - `Ingress.yaml`: Example ingress manifest.
    - **Helm_Charts/**
      - **Chart1/**
        - `templates/`: Templates for the chart.
        - `values.yaml`: Default values for the chart.
      - **Chart2/**
        - `templates/`: Templates for the chart.
        - `values.yaml`: Default values for the chart.
    - **Tutorials/**
      - `Kubernetes_Basics.md`: Getting started with Kubernetes.
      - `Helm_Tutorial.md`: Tutorial on using Helm.
      - `K8s_Advanced_Topics.md`: Advanced topics in Kubernetes.
    - **Cheat_Sheets/**
      - `K8s_Cheat_Sheet.md`: Quick reference guide for Kubernetes commands.
      - `Helm_Cheat_Sheet.md`: Quick reference guide for Helm commands.

- **04_Monitoring_and_Logging/**
  - **Prometheus_Grafana/**
    - **Prometheus_Config/**
      - `prometheus.yml`: Main Prometheus configuration file.
      - `alert_rules.yml`: Alerting rules for Prometheus.
    - **Grafana_Dashboards/**
      - `Dashboard1.json`: JSON file for Grafana dashboard 1.
      - `Dashboard2.json`: JSON file for Grafana dashboard 2.
    - **Tutorials/**
      - `Prometheus_Tutorial.md`: Getting started with Prometheus.
      - `Grafana_Tutorial.md`: Getting started with Grafana.
  - **ELK_Stack/**
    - **Elasticsearch_Config/**
      - `elasticsearch.yml`: Main Elasticsearch configuration file.
      - `index_settings.json`: Index settings for Elasticsearch.
    - **Logstash_Config/**
      - `logstash.conf`: Main Logstash configuration file.
      - `pipelines.yml`: Pipeline configuration for Logstash.
    - **Kibana_Dashboards/**
      - `Dashboard1.json`: JSON file for Kibana dashboard 1.
      - `Dashboard2.json`: JSON file for Kibana dashboard 2.
    - **Tutorials/**
      - `Elasticsearch_Tutorial.md`: Getting started with Elasticsearch.
      - `Logstash_Tutorial.md`: Getting started with Logstash.
      - `Kibana_Tutorial.md`: Getting started with Kibana.
  - **Tutorials/**
    - `Monitoring_Basics.md`: Basics of monitoring and logging.
    - `Setting_Up_Alerts.md`: Setting up alerts with monitoring tools.
    - `Log_Analysis.md`: Log analysis best practices.

### 4. [Data Science](https://github.com/mohammadtmz/Data_Science)
This repository contains tools, techniques, and practices related to data science, including Python libraries, data processing, machine learning, and MLOps.

- **01_Python_for_Data_Science/**
  - **Pandas/**
    - `README.md`: Overview of Pandas.
    - `DataFrames.md`: Working with Pandas DataFrames.
    - `Data_Cleaning.md`: Data cleaning with Pandas.
    - **Tutorials/**
      - `Pandas_Basics.md`: Getting started with Pandas.
      - `Pandas_Advanced.md`: Advanced Pandas techniques.
  - **NumPy/**
    - `README.md`: Overview of NumPy.
    - `Arrays.md`: Working with NumPy arrays.
    - `Linear_Algebra.md`: Linear algebra with NumPy.
    - **Tutorials/**
      - `NumPy_Basics.md`: Getting started with NumPy.
      - `NumPy_Advanced.md`: Advanced NumPy techniques.
  - **Matplotlib_Seaborn/**
    - `README.md`: Overview of Matplotlib and Seaborn.
    - `Matplotlib.md`: Data visualization with Matplotlib.
    - `Seaborn.md`: Data visualization with Seaborn.
    - **Tutorials/**
      - `Matplotlib_Tutorial.md`: Getting started with Matplotlib.
      - `Seaborn_Tutorial.md`: Getting started with Seaborn.
  - **Scikit_Learn/**
    - `README.md`: Overview of Scikit-Learn.
    - `Supervised_Learning.md`: Supervised learning with Scikit-Learn.
    - `Unsupervised_Learning.md`: Unsupervised learning with Scikit-Learn.
    - **Tutorials/**
      - `Classification_Tutorial.md`: Classification with Scikit-Learn.
      - `Regression_Tutorial.md`: Regression with Scikit-Learn.
      - `Clustering_Tutorial.md`: Clustering with Scikit-Learn.

- **02_Data_Processing/**
  - `README.md`: Overview of data processing techniques.
  - **ETL_Pipelines/**
    - `README.md`: Overview of ETL pipelines.
    - `Pipeline1.md`: ETL pipeline example 1.
    - `Pipeline2.md`: ETL pipeline example 2.
  - **Data_Cleaning/**
    - `README.md`: Overview of data cleaning techniques.
    - `Missing_Values.md`: Handling missing data.
    - `Outlier_Detection.md`: Outlier detection and removal.
    - `Data_Normalization.md`: Normalizing data.
  - **Big_Data/**
    - `README.md`: Overview of big data tools.
    - `Hadoop.md`: Introduction to Hadoop.
    - `Spark.md`: Introduction to Apache Spark.
    - **Tutorials/**
      - `Hadoop_Tutorial.md`: Getting started with Hadoop.
      - `Spark_Tutorial.md`: Getting started with Spark.

- **03_Machine_Learning/**
  - **Supervised_Learning/**
    - `README.md`: Overview of supervised learning.
    - `Linear_Regression.md`: Linear regression with examples.
    - `Decision_Trees.md`: Decision trees and random forests.
    - **Tutorials/**
      - `Regression_Tutorial.md`: Linear regression tutorial.
      - `Classification_Tutorial.md`: Classification tutorial.
  - **Unsupervised_Learning/**
    - `README.md`: Overview of unsupervised learning.
    - `K_Means.md`: K-means clustering.
    - `PCA.md`: Principal Component Analysis (PCA).
    - **Tutorials/**
      - `Clustering_Tutorial.md`: Clustering tutorial.
      - `Dimensionality_Reduction.md`: Dimensionality reduction tutorial.
  - **Deep_Learning/**
    - `README.md`: Overview of deep learning.
    - **TensorFlow/**
      - `Introduction.md`: Introduction to TensorFlow.
      - `CNNs.md`: Convolutional Neural Networks (CNNs).
      - `RNNs.md`: Recurrent Neural Networks (RNNs).
    - **PyTorch/**
      - `Introduction.md`: Introduction to PyTorch.
      - `NLP.md`: Natural Language Processing with PyTorch.
      - `GANs.md`: Generative Adversarial Networks (GANs).
    - **Tutorials/**
      - `TensorFlow_Tutorial.md`: Getting started with TensorFlow.
      - `PyTorch_Tutorial.md`: Getting started with PyTorch.
  - **Tutorials/**
    - `ML_Basics.md`: Basics of machine learning.
    - `Model_Evaluation.md`: Model evaluation and metrics.
    - `Feature_Engineering.md`: Feature engineering techniques.

- **04_DevOps_for_Data_Science/**
  - **MLOps/**
    - `README.md`: Overview of MLOps.
    - `CI_CD_for_ML.md`: CI/CD pipelines for machine learning.
    - **Tutorials/**
      - `MLOps_Pipeline.md`: Setting up an MLOps pipeline.
      - `Monitoring_ML_Models.md`: Monitoring models in production.
  - **Data_Versioning/**
    - `README.md`: Overview of data versioning.
    - `DVC.md`: Introduction to Data Version Control (DVC).
    - **Tutorials/**
      - `DVC_Tutorial.md`: Getting started with DVC.
      - `Data_Management_Best_Practices.md`: Best practices for data management.
  - **Model_Deployment/**
    - `README.md`: Overview of model deployment.
    - `Deploying_with_Docker.md`: Deploying ML models with Docker.
    - `Deploying_with_Kubernetes.md`: Deploying ML models with Kubernetes.
    - **Tutorials/**
      - `Docker_Deployment_Tutorial.md`: Tutorial on deploying models with Docker.
      - `Kubernetes_Deployment_Tutorial.md`: Tutorial on deploying models with Kubernetes.
  - **Monitoring/**
    - `README.md`: Overview of model monitoring.
    - `Performance_Metrics.md`: Key performance metrics for ML models.
    - `Logging_for_ML.md`: Setting up logging for ML models.
    - **Tutorials/**
      - `Monitoring_Tutorial.md`: Getting started with monitoring ML models.
      - `Alerting_Tutorial.md`: Setting up alerts for model performance.

- **05_Data_Science_Projects/**
  - **01_Project_Name/**
    - `README.md`: Overview of the project.
    - **Data/**
      - `dataset1.csv`: Example dataset 1.
      - `dataset2.csv`: Example dataset 2.
      - `README.md`: Description of the datasets.
    - **Notebooks/**
      - `Analysis.ipynb`: Jupyter notebook with data analysis.
      - `Modeling.ipynb`: Jupyter notebook with model development.
    - **Models/**
      - `model.pkl`: Serialized trained model.
      - `model_metrics.json`: Performance metrics of the model.
    - **Reports/**
      - `Report.pdf`: Final project report.
      - `Presentation.pptx`: Project presentation.

### 5. [Projects](https://github.com/mohammadtmz/Projects)
This repository contains real-world projects and case studies demonstrating practical applications of cloud, DevOps, and data science skills.

- **01_Project_Name/**
  - `README.md`: Overview of the project.
  - `Architecture.png`: Architecture diagram (if applicable).
  - **Terraform/**
    - `main.tf`: Main Terraform configuration file.
    - `variables.tf`: Terraform variables file.
  - **Ansible/**
    - `playbook.yml`: Main Ansible playbook.
    - **roles/**
      - **web_server/**: Role for web server setup.
      - **db_server/**: Role for database server setup.
  - **Docker_Kubernetes/**
    - `Dockerfile`: Dockerfile for containerizing the application.
    - `docker-compose.yml`: Docker Compose file for multi-container setup.
    - **k8s/**
      - `deployment.yaml`: Deployment manifest.
      - `service.yaml`: Service manifest.
      - `ingress.yaml`: Ingress manifest.

### 6. [Resources](https://github.com/mohammadtmz/Resources)
This repository contains additional learning resources including recommended books, courses, and tools related to cloud, DevOps, and data science.

- **Books/**
  - `Cloud_Engineering.md`: Recommended books for cloud engineering.
  - `DevOps.md`: Recommended books for DevOps.
  - `Data_Science.md`: Recommended books for data science.

- **Courses/**
  - `Cloud_Courses.md`: Recommended cloud-related courses.
  - `DevOps_Courses.md`: Recommended DevOps-related courses.
  - `Data_Science_Courses.md`: Recommended data science-related courses.

- `Tools_and_Utilities.md`: List of useful tools, utilities, and extensions.

---

Thank you for exploring my GitHub repositories! Feel free to explore each section and the various tools and resources I've compiled. Contributions and feedback are always welcome.
