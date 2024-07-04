# reddit-clone

In this we have deploy this project in aws using eks service.
in this project we have use terrafrom to build ec2 instance and update and download all the required files.
We have also made jankins file to automate all the work or say maximum work...
In jenkins filr we firstly clear our workspace then we checkout the code from github.           
We also did sonarqube analysis to check our code quality for sonarqube to run we had made docker container to run it.    
We have also use quality gates. 
Then we install all the dependency to run our code.    
We tehn check through trivy.     
then make dockerimage and push that image in docker hub.         
then we again perform trivy image scan to check all the are running fine.     
Then if the steps are pass then we trigger our CD pipeline.
We have also use promthenus grafana and argocd to check all the things are running fine.      

this is the output page
![Screenshot 2024-07-03 185230](https://github.com/rachit1a/reddit-clone/assets/172263244/32e1bae3-c4b3-4859-b3c6-b75a8a8bd93e)

Argocd SS
![Screenshot 2024-07-03 184919](https://github.com/rachit1a/reddit-clone/assets/172263244/e16f5628-677f-44c7-a35f-ca1c3eb3ca8b)

![Screenshot 2024-07-03 184622](https://github.com/rachit1a/reddit-clone/assets/172263244/9a092b09-040c-423f-a95a-d6f9c650a3f2)
![Screenshot 2024-07-03 182949](https://github.com/rachit1a/reddit-clone/assets/172263244/aff455df-3262-45b2-b410-084ad758def3)

grafanaSS
![Screenshot 2024-07-03 181137](https://github.com/rachit1a/reddit-clone/assets/172263244/bd86e0e3-a7b1-4195-8ea0-d7b825ec6031)
![Screenshot 2024-07-03 181217](https://github.com/rachit1a/reddit-clone/assets/172263244/ee58f21b-87e2-48a7-a3dd-dcc450d0c402)
![Screenshot 2024-07-03 181348](https://github.com/rachit1a/reddit-clone/assets/172263244/6b2aaaf4-dcdb-495b-aa09-89da2aad43f2)
