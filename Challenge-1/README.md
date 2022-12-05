Challenge #1

A 3-tier environment is a common setup. Use a tool of your choosing/familiarity create these resources. Please remember we will not be judged on the outcome but more focusing on the approach, style and reproducibility.

The template will deploy the following components:
1. VPC
2. Route Table
3. Internet Gateway
4. Attaches Internet Gateway to the VPC you just created
5. 2 Public Subnets
6. Scaling Policy for Public Subnets
7. Route Table for Public Subnets
8. Associate the Public Subnets to the Route Table
9. Security group with HTTP & SSH to open to 0.0.0.0/0
10. Launch Template with Bootstrap script to install & launch Apache
11. AutoScaling Group for Public Subnets
12. Scaling Policy
13. 4 Private Subnets — two in us-east1a & two in us-east1b
14. AutoScaling Group for two Private Subnets in the Application tier