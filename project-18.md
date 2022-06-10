# Documentation of Project 18

1. I created a modules folder so as to make my workspace more neater and easy to access

2. In the modules folder, I created 7 folders namely;

a. ALB:- for creating loadbalancers and target groups

b. Autoscaling:- for creating autoscaling groups

c. Compute:- for creatinh jenkins,sonarqube and artifactory server

d. EFS:-for creating elastic file system and access points

e. RDS:- for creating database

f. Security:- for creating security groups and their respective inbound rules

g. VPC:- for creating VPC, public and private subnets
       ![Project18](images/image1.PNG)
       ![Project18](images/image2.PNG)
       ![Project18](images/image3.PNG)
       ![Project18](images/image4.PNG)
       ![Project18](images/image5.PNG)
       ![Project18](images/image6.PNG)
       ![Project18](images/image7.PNG)
       ![Project18](images/image8.PNG)
       ![Project18](images/image9.PNG)


3. I created a some files in my workspace namely;
a. main.tf
b. providers.tf
c. variables.tf

     ![Project18](images/image10.PNG)
     ![Project18](images/image11.PNG)
     ![Project18](images/image12.PNG)


4. I ran a terraform plan and it worked without issues
     
     ![Project18](images/image13.PNG)
     ![Project18](images/image14.PNG)
     ![Project18](images/image15.PNG)
     ![Project18](images/image16.PNG)
     ![Project18](images/image17.PNG)
     ![Project18](images/image18.PNG)
     ![Project18](images/image19.PNG)
     ![Project18](images/image20.PNG)
     ![Project18](images/image21.PNG)
     ![Project18](images/image22.PNG)
     ![Project18](images/image23.PNG)
     ![Project18](images/image24.PNG)
     ![Project18](images/image25.PNG)
     ![Project18](images/image26.PNG)
     ![Project18](images/image27.PNG)
     ![Project18](images/image28.PNG)
     ![Project18](images/image29.PNG)
     ![Project18](images/image30.PNG)
     ![Project18](images/image31.PNG)
     ![Project18](images/image32.PNG)
     ![Project18](images/image33.PNG)
     ![Project18](images/image34.PNG)

4. I ran `terraform apply` command and it worked successfully
     
     ![Project18](images/image35.PNG)
     ![Project18](images/image36.PNG)

5. I confirmed everything that has been created in my aws console
     
     ![Project18](images/image37.PNG)
     ![Project18](images/image38.PNG)
     ![Project18](images/image39.PNG)
     ![Project18](images/image40.PNG)
     ![Project18](images/image41.PNG)
     ![Project18](images/image42.PNG)
     ![Project18](images/image43.PNG)
     ![Project18](images/image44.PNG)
     ![Project18](images/image45.PNG)
     ![Project18](images/image455.PNG)
     ![Project18](images/image46.PNG)
     ![Project18](images/image47.PNG)
     ![Project18](images/image48.PNG)
     ![Project18](images/image49.PNG)
     ![Project18](images/image50.PNG)

6.   I created a new file in my workspace named "backend.tf" to use my S3 bucket as a backend
      
      ![Project18](images/image51.PNG)

7.  I initialized terraform to make effects to my changes
     
     ![Project18](images/image52.PNG)

8. I checked my aws console to confirm what I did
    
    ![Project18](images/image53.PNG)
    ![Project18](images/image54.PNG)
    ![Project18](images/image55.PNG)

9. I destroyed my infrastructure so as to avoid unneccessary debts but I commented out the commands in my 'backend.tf' file so as not to delete terraform.tfstate file
       
        ![Project18](images/image56.PNG)