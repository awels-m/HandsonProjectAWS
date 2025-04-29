# HandsonProjectAWS

# PROJECT OVERVIEW
This project is an overview on cloud computing and it is designed to guide me through the intricacies of AWS  and focusing on IAM. 

# PURPOSE OF THE PROJECT
the project aims at expanding my knowledge on cloud computing and it aims at guiding me through the intricacies of Aws and the use of IAM. it also aims at aiding me through the basic knowlege on  cloud computing and the use of AWS.
the purpose of the project is to help me learn the process of creating an IAM Account. it is also to guide me through the process of creating a secured enviroment that reflect real world situations and challenges. it is alos to help me gain the fundamental knowledge of IAM, to learn how to manage access to AWS resources and learn the best practices for securing my cloud enviroment. in summary the purpose of this projects are 
1. gain a solid understanding of AWS, IAM including users, groups, policies and roles
2. learn how to apply IAM Cconcept to secure a fintech startup's cloud infastructure
3. develope practical skills in using AWS management console to manage IAM 
4. To understand the significance of secure access managements and its impacts on compliance and data security in the fintech industry. 


# OBJECTIVE OF THE PROJECT
The objective of the project is to help me gain mastery in cloud computing using AWS and through the use of IAM. it also intends to educate me on the use of cloud computing in real world situation. 
1. how to create an IAM account
2. how to create a secured enviroment that reflect real world situations and challenges 
3. to learn the fundamental of IAM 
4. to learn how to manage access to AWS Resources 
5. to learn the best practices for securing my cloud enviroment. 

# PRACTICAL EXPERIENCE OF THE TASK 

## CREATING OF POLICIES

The first thing to do is to log into the AWS Console using the administrator account and then navigate to the IAM dashboard. the images below depicts this

![1img](./1img.png)
![2img](./2img.png)
![3img](./3img.png)

the next thing is to create policy for the development team as well as the analyst team. i am going to navigate to the policy part of the IAM Console and create a new policy. the images below depict this. 
![4img](./4img.png)
![5img](./5img.png)
![6img](./6img.png)
![7img](./7img.png)
![8img](./8img.png)
![9img](./9img.png)
![10img](./10img.png)
![11img](./11img.png)
![12img](./12img.png)
![13img](./13img.png)
![14img](./14img.png)
![15img](./15img.png)
![16img](./16img.png)
![17img](./17img.png)
![18img](./18img.png)

## CREATING OF GROUPS
in the IAM Console, i will navigat to the group part and create groups for the developement team and the analyst team. the images below depicts this. 

![19img](./19img.png)
![201img](./201mg.png)
![21img](./21img.png)
![22img](./22img.png)
![23img](./23img.png)
![24img](./24img.png)

## CREATING OF USERS
in the IAM Console, i will navigate to the user part and the create the two different users 'john' 'mary' for both the development team and the analyst team groups. the image below depicts this 
![25img](./25img.png)
![26img](./26img.png)
![27img](./27img.png)
![28img](./28img.png)
![29img](./29img.png)
![30img](./30img.png)
![31img](./31img.png)
![32img](./32img.png)
![33img](./33img.png)
![34img](./34img.png)


## TESTING AND VALIDATION 
### TESTING JOHN'S ACCESS
I am going to log in as John and mary and confirm they have access to all i granted. the images below depicts this. 
The image below shows that i have syccessfully signed in as john and john has all tge access i earlier granted. 
![40img](./40img.png)

The image above shows that John has all the access granted to him. 

## Testibg and Validation 
### Testing Mary's Access
I also logged in as Mary and confirmed that she has access to all that I ahve granted. 


## Implementing Multi-facto Authentication
I first went to the users and selected John and went on to do same for Mary. then i clicked on enable MFA. afterwhich, i clicked on next and opened my google authenticator since i selected authenticator app. Then, i scanned the qr code and then filled in the space with the MFA Code. 

Once this was concluded, i have successfully enabled MFA for John and Mary. the images below depicts this. 
![41img](./41img.png)
![42img](./42img.png)
![43imh](./43img.png)
![44img](./44img.png)
![45img](./45img.png)
![46img](./46img.png)
![47img](./47img.png)

# CONCLUSION
IAM (Identity and Access Management) in AWS is the service that controls who can do what in your AWS accoumt.

Main roles of IAM:
	1.	Authentication – Verifies who is trying to access AWS (e.g. user, application).
	2.	Authorization – Decides what actions they are allowed to perform (based on policies).
	3.	User & Role Management – Lets you create users, groups, and roles with specific permissions.
	4.	Fine-Grained Access Control – You can define rules like:
“User A can only read from S3, but can’t delete anything.”
Why it’s important:

Without IAM:
	Everyone would have full access to everything — a massive security risk.
	IAM enforces the principle of least privilege: only give access that’s truly needed.

