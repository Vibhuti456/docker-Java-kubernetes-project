## Project Description
The Docker Java Kubernetes Project is a sample microservices-based application designed to demonstrate how to build, containerize, and deploy Java applications using Docker and Kubernetes.

The application consists of three independent Java microservices:

Product Catalogue – Provides product details and descriptions.

Stock Manager – Manages and reports product inventory levels.

Shop Front – Acts as the main frontend API, aggregating data from the Product Catalogue and Stock Manager services to present to the user.

Each microservice is packaged into its own Docker image and deployed as a separate Kubernetes deployment. Kubernetes Services are used to enable communication between microservices and expose endpoints for access within the cluster or externally.

### Application Shopfront
<img width="1792" height="810" alt="image" src="https://github.com/user-attachments/assets/3b6cca78-39f6-439e-9fc3-e5fdf3454f8c" />

### Products
<img width="1801" height="816" alt="image" src="https://github.com/user-attachments/assets/36168fe2-a55f-4597-8cc0-b9a0865bbef0" />

### Stocks
<img width="1810" height="808" alt="image" src="https://github.com/user-attachments/assets/ad6ae414-3162-4ac4-a3f7-a1c0d5278723" />
