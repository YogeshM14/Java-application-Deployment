# Java-application-Deployment

Step 1: Create a VPC
![Screenshot (16)](https://github.com/user-attachments/assets/191037fb-e0e1-4cf8-bda5-04dd972a5a98)

Step 2: Create a Internet Gateway
![Screenshot (17)](https://github.com/user-attachments/assets/4695d54f-6c71-4170-9760-a026ba5fb4ee)

Step 3: Attach the Internet gateway to VPC
![Screenshot (18)](https://github.com/user-attachments/assets/2f623a64-979e-463f-b501-8796b04a88fe)

Step 4: Create public and private Subnets
![Screenshot (19)](https://github.com/user-attachments/assets/bd17b3f1-4e80-43f5-aa0e-074bd6dd9da4)

![Screenshot (20)](https://github.com/user-attachments/assets/0c651050-d3eb-4928-8995-70be53a21516)

Step 5: Create Public and Private Route Tables
![Screenshot (21)](https://github.com/user-attachments/assets/5cd71aea-a950-4d97-8c2e-810c40f5d595)

Step 6: Create a NAT gateway and edit route to priavte route table 
![Screenshot (28)](https://github.com/user-attachments/assets/0a861cc6-ef32-40ef-a982-fe99000e1320)

Step 7: Your VPC setup should like this 
![Screenshot (29)](https://github.com/user-attachments/assets/94a4d1ee-21b2-4ad4-ab8e-2a2c945f391c)

Step 8: Create a ubuntu server in EC2 Instance and connect
![Screenshot (30)](https://github.com/user-attachments/assets/f2000c68-5947-4def-8f9e-f17eea8a3d22)

![Screenshot (31)](https://github.com/user-attachments/assets/33bcd97c-8905-4dde-ae8e-c160c48ed1e4)

Step 9: Create a MySQL database in RDS 
![Screenshot (44)](https://github.com/user-attachments/assets/c7ff1e45-8a9e-4886-b91d-8bec4fa7dc86)

Step 10: upload the Java application file in the server directory 
![Screenshot (31)](https://github.com/user-attachments/assets/d0b3df08-79f3-4fe1-91c4-ab202d8104c2)

Step 11: Install my-sql-client ,maven and openjdk-8-jdk

Step 12: Connect the database to the server using the command and the endpoint of MySQL
![Screenshot (34)](https://github.com/user-attachments/assets/9f5b9374-ac22-4332-b691-277063044a88)

Step 13: Configure the application properties 
![Screenshot (35)](https://github.com/user-attachments/assets/1d741a2a-a4ca-44e9-94f8-c3cd844c4dec)

Step 14: Now compile and run the Java application
![Screenshot (36)](https://github.com/user-attachments/assets/213cf97c-6213-488d-b493-39511da91fc2)

Step 15 : Add the port number of Java application which given in the application properties (default 8080) to the security groups of the server
![Screenshot (37)](https://github.com/user-attachments/assets/bcc77177-6aa8-460d-b1d6-e62db2001bae)

Step 16: Copy and paste the public ip address in the browser along with port number (public ip:8080)
![Screenshot (38)](https://github.com/user-attachments/assets/9ce7a300-12b1-41c0-b4b6-0b4de69ab2cd)














