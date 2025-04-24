# Introduction to Cloud computing - Security and Identity management

- Login to the AWS account
![image](https://github.com/user-attachments/assets/b3e23748-e582-4339-a9f8-a486eb9eac19)
- Navigate to the IAM dashboard
  ![image](https://github.com/user-attachments/assets/26a2d9d3-6e78-495f-b12c-10328f27504b)
- Go to Policies
  ![image](https://github.com/user-attachments/assets/e30384ba-93d3-426b-985d-b38ca80571bf)
  - Click on Create Policy
    ![image](https://github.com/user-attachments/assets/e7797c37-e9d2-4449-b860-cd0cd97a339e)
    - Select service
      ![image](https://github.com/user-attachments/assets/02871e46-3a73-42e4-8aac-e650e65d2eed)
      - Select the the service and actions allowed
        ![image](https://github.com/user-attachments/assets/98cad20f-479d-4169-8a68-606f6e6242c7)
        - Review and Create
          ![image](https://github.com/user-attachments/assets/4fd5dfd9-280d-4fad-b18f-f438c87bf51c)

        -  ![image](https://github.com/user-attachments/assets/7234c179-5f1c-43f1-8c0d-6e4008a81b8a)

         - ![image](https://github.com/user-attachments/assets/ff236939-af33-4f7e-87e3-e8d53c2b65bf)
       
         - Same done for Data analyst team
           ![image](https://github.com/user-attachments/assets/801a33ff-f4ff-46e1-8e2b-bc0c710fb7ff)

           - Goto your User group module and Create a new user group
            ![image](https://github.com/user-attachments/assets/cc95c337-8f82-4779-b56f-e1bc20f53b3f)


             - Enter the name of the team
               ![image](https://github.com/user-attachments/assets/83bd125c-bf86-4bce-84b2-5adbe1695c64)

               - Assign the Created policy
                 ![image](https://github.com/user-attachments/assets/6caf5844-5a88-4cb0-9746-a6ffa38dd268)

                 - It has been created
                   ![image](https://github.com/user-attachments/assets/0fb6b064-5071-4aaa-8a14-46c412f76c16)
                   - User Group created for the Data analyst team
                     ![image](https://github.com/user-attachments/assets/16684c5d-74bd-40a3-aecb-1a4816776343)

             ## Creating IAM USERs

             - Create IAM user for John, Gott IAM user and click on Create
               ![image](https://github.com/user-attachments/assets/a94e4620-b1f0-4546-98a3-d6e63d8c1fea)

               - Enter the name and Create
                 ![image](https://github.com/user-attachments/assets/9e0f1398-49e4-4bbc-b96c-5ed2efe95f4f)

                 - ![image](https://github.com/user-attachments/assets/0d96d3c5-4e2f-4d28-b4ff-ec74b3963a1b)
                
                 - Add user to the Development user group
                   ![image](https://github.com/user-attachments/assets/b2d168a2-12ad-41ef-9075-23d4b6d9e342)

                   - Create user
                     ![image](https://github.com/user-attachments/assets/5bd0d680-009c-4782-9c07-fbcfdaad3cc9)

                     - User profile for Mary
                       ![image](https://github.com/user-attachments/assets/1d84a208-669b-4959-a3a0-ab280791eb7b)

                       - ![image](https://github.com/user-attachments/assets/1d6ca03a-005b-4859-8a33-b53cf3c1889a)


                    ## Johns Access Test
                      ![image](https://github.com/user-attachments/assets/0d72f329-a5b1-49f6-a70c-da552218b112)
                      - Access to Ec2 module
                       ![image](https://github.com/user-attachments/assets/560cd9c2-23d7-47e2-87fa-aa227e06499c)

                      - Creating Ec2 with John's access
                        ![image](https://github.com/user-attachments/assets/ac21fe1a-126d-4db6-86c3-6f5485f1e7b3)

                        - ![image](https://github.com/user-attachments/assets/57918be6-542a-4c55-9321-a001e756805c)
                        - Created Ec2 successfully
                          ![image](https://github.com/user-attachments/assets/16a61a35-f505-410c-add3-11673fb7f7ab)

                         ## Testing Mary's Accesss

                        ![image](https://github.com/user-attachments/assets/ced2c7af-5c81-4a17-bc91-306dcbdefacf)
                           - Access to S3 module
                             ![image](https://github.com/user-attachments/assets/530fb74f-0290-487f-827a-fd0051aa9fe7)
                             - Creating S3 bucket with Mary's access
                             ![image](https://github.com/user-attachments/assets/b6565dff-7034-4aac-9b50-7a0791a23292)
                             - Created S3 bucket successfully
                             ![image](https://github.com/user-attachments/assets/2fe35866-bb8c-4689-b245-37e5db992f19)

## Validating group policies
- John's access validation
- Cannot create s3 bucket
  ![image](https://github.com/user-attachments/assets/ad0ea16c-9d03-4d5d-abe6-c2c919ea50ac)


- Mary's access validation
  - ![image](https://github.com/user-attachments/assets/cadf14aa-a654-4121-bcec-9d7e33af329d)
  - ![image](https://github.com/user-attachments/assets/cb308519-65ee-409d-baab-6b3023d49078)
  - ![image](https://github.com/user-attachments/assets/64785554-966f-44b4-b6bc-98830184bd35)
  - ![image](https://github.com/user-attachments/assets/5894fe07-a0ed-4ced-81ac-8474c2cb29a8)
 
- Cannot launch instance
  ![image](https://github.com/user-attachments/assets/6330541b-b2e3-4d6c-84da-2b891cb38756)



  ## Implementing MFA
  -For John Go to the user's  mfa module
    ![image](https://github.com/user-attachments/assets/27fe377d-efa4-4e00-bec7-ec4a39559e33)
    - Select authenticator app
      ![image](https://github.com/user-attachments/assets/6b1741da-77e9-4033-9005-7a5fa748566d)
      - Add mfa
        ![image](https://github.com/user-attachments/assets/fbf8398e-ff78-4315-844b-aa816ce00376)
        - Mfa added successfully
          ![image](https://github.com/user-attachments/assets/472b7ff2-b5a0-4a7c-94de-715d7596a6a6)

          - For Mary Go to the user's  Mfa module
            ![image](https://github.com/user-attachments/assets/c31abdca-da6f-4b7b-ae0f-de4cbcee67ef)
            - Mfa added successfully
            ![image](https://github.com/user-attachments/assets/697f26a4-4d48-4888-ac38-78e8dcf4e4eb)


            










  
 

                             
                        













               













