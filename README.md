# CLOUD-LAMBDA
cost optimization

# Here firstly we created EC2 instance and volume of EC2 instance.
![Screenshot (1224)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/801b72c9-7c7c-4cd2-adb3-c38c19556e7b)
![Screenshot (1225)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/7993b39d-4074-49dc-bbbc-a767249a011f)

# Created Snapshot of EC2 instance
![Screenshot (1230)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/98941fe0-087a-4bd5-8de5-2378dfee2b58)

# Navigated to lamda dashboard
![Screenshot (1202)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/fff98efc-9a99-4f1d-a4e2-cd04ac82fdf7)

# Created lamda function 
Click on create function option and created lamda function
![Screenshot (1205)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/24577278-897e-40dd-8919-e1aca3342a48)
# here is lamda function is created
![Screenshot (1206)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/fa8534bf-8aa1-4378-ad55-54463dde5bee)
# Now in click on Code source section
![Screenshot (1208)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/35a6a198-6a47-4626-8b96-97008d05cb84)
# imported my python code and clicked on deploy option
  here we created test event
![Screenshot (1211)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/065c05b9-b98f-4aa7-9bf1-15849ea670de)
![Screenshot (1209)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/0d5c81aa-d997-473c-ba1f-909b31c3e53c)
# Now test the code,it gives error as follows
![Screenshot (1212)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/1fcfed58-c4bf-4b40-b695-713434875a2b)
# Do the following settings for remove errors
 here change the timeout limit in general configuration section from 3 sec to 10 sec
 ![Screenshot (1214)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/7f830620-391b-4a1a-806e-e2e3b28c0871)
 ![Screenshot (1213)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/c15891cf-9eaf-4335-8025-4962179a1004)
# Now go to the permissions
 click on Role name and create new policy for our lamda function
 ![Screenshot (1215)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/440ef70d-b973-48e5-aff4-39684f864836)
# It will navigate to IAM-ROLES dashboard 
 click on add permissions -> create inline policy
 ![Screenshot (1217)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/2b5f5f64-6671-4c71-a614-b29827c7f86f)
# now select the EC2 service
 ![Screenshot (1218)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/9ad13c58-d1e6-4b51-bd46-83d84280d131)
# give permissions as follows
 ![Screenshot (1219)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/a526c03e-ff8c-49c3-bc7e-7a4fc373849d)
 ![Screenshot (1220)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/3ab66acd-3a60-42ff-8fa2-7591b3f18ba9)
 ![Screenshot (1221)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/5b83b1d8-6cb8-4863-b686-420bf0e6eae0)
 ![Screenshot (1222)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/19d53ba5-9c76-40f9-9562-d04f6c280688)
# after giving permissions give policy name as follows
 ![Screenshot (1223)](https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/21e54556-1c98-4f5d-9d3a-18508b8924e5)
# Now test the code
  Code contains permission as if we terminate the EC2 instance then it automatically deletes the volume and snapshot of the EC2 instance
  https://github.com/ShrutiGavali/CLOUD-LAMBDA/assets/122098190/5bbd649e-f26a-43ab-b627-094406404ca1.mp4











