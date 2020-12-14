# **Fursa Kubernetes homework**
The project inculde two yaml files : 
- apache.yml 
    - pull & install apache image 
    - run service on targer port  80 

- mysql: 
  - pulll & install mysql image , default port 3306 , datapase password : "password"
  - run service on targer port  3306 

# **How to use**: 
command line : 
 - **kubectl apply -f apache.yml**
 - **kubectl apply -f mysql.yml**

or just run this command : 

 - **kubectl apply -f .** 
  