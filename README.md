Creating Resources and Setting up Cloud Armor:



1.  Creating a VM with nginx 

Creating a VM with nginx installed

![Screenshot 2024-09-16 at 10 11 06 AM](https://github.com/user-attachments/assets/354e9562-7488-4908-8d5e-dab1644c9a12)


![Screenshot 2024-09-16 at 10 13 43 AM](https://github.com/user-attachments/assets/93e66da4-bd98-48d0-a492-89c7039fdfbd)


![Screenshot 2024-09-16 at 10 14 11 AM](https://github.com/user-attachments/assets/c58c8f19-92a3-4d6d-ab13-06a7b71bdf92)


![Screenshot 2024-09-16 at 10 14 33 AM](https://github.com/user-attachments/assets/da15ae07-4cf2-4beb-92ff-c1d641f4bbdf)

							VM Created

![Screenshot 2024-09-16 at 10 15 07 AM](https://github.com/user-attachments/assets/44046065-fcfc-46f3-94f3-67220fee28ae)

![Screenshot 2024-09-16 at 10 15 28 AM](https://github.com/user-attachments/assets/fb2e5e65-3707-4abd-8815-a215c1332c90)

					Creating an Unmanaged Instance Group:

![Screenshot 2024-09-16 at 10 16 41 AM](https://github.com/user-attachments/assets/47d4ffaa-7225-4657-94c9-d1bf2213982c)

![Screenshot 2024-09-16 at 10 16 58 AM](https://github.com/user-attachments/assets/aa24b915-c3c9-4c72-8bc7-4f40691b7f17)

						Creating a Load Balancer:

![Screenshot 2024-09-16 at 10 17 47 AM](https://github.com/user-attachments/assets/e7c8dbff-7fba-4c8f-a311-a3796112c239)

![Screenshot 2024-09-16 at 10 18 58 AM](https://github.com/user-attachments/assets/58e7a0bd-c440-4aa6-b4bf-0349b9fb0f80)

Testing the Nginx site after Load Balancer Creation:

![Screenshot 2024-09-16 at 10 20 50 AM](https://github.com/user-attachments/assets/72cf5aff-f7e2-4f11-a37d-20cc125a678b)


2: Setting up Cloud Armor Rules

					Creating new Rule to Deny-All Traffic

![Screenshot 2024-09-16 at 10 23 22 AM](https://github.com/user-attachments/assets/b7bb8306-fbd1-48d9-b9ef-af8be34f051f)

						Nginx Site after Rule is made

![Screenshot 2024-09-16 at 10 45 10 AM](https://github.com/user-attachments/assets/062ee42d-3129-464f-8a4c-6460637927df)

						Creating Allow-All Rule

![Screenshot 2024-09-16 at 10 46 05 AM](https://github.com/user-attachments/assets/41d0b877-1917-427f-9829-baade806e5b7)

![Screenshot 2024-09-16 at 10 46 35 AM](https://github.com/user-attachments/assets/e0afa04b-8732-42a1-8af4-6769aec35877)

						Nginx site after Allow-All Rule:

![Screenshot 2024-09-16 at 10 47 11 AM](https://github.com/user-attachments/assets/10ca9567-bb33-4d27-abd7-84c0ccabe0de)


3. Adding Rule for Cloud shell IP

						Allowing Cloud Shell IP only

![Screenshot 2024-09-16 at 10 48 31 AM](https://github.com/user-attachments/assets/ea6e6220-bf09-4b1a-a465-57d535efa9d4)

![Screenshot 2024-09-16 at 10 48 49 AM](https://github.com/user-attachments/assets/508191bf-04e1-49d4-9641-dd7211499dff)

![Screenshot 2024-09-16 at 10 49 06 AM](https://github.com/user-attachments/assets/c0164400-fa4d-477e-ab72-19107fcea08a)

4. Setting up more Rules for Access and Denial

					Creating a GoodPath folder and BadPath folder then nano index.html

![Screenshot 2024-09-16 at 10 50 48 AM](https://github.com/user-attachments/assets/cbecf9f6-c6f3-4471-886b-412a78c29207)

![Screenshot 2024-09-16 at 10 51 21 AM](https://github.com/user-attachments/assets/690a5fbf-3f91-44bb-9e41-3ac56bebd416)

							Navigating to the Goodpath

![Screenshot 2024-09-16 at 10 51 52 AM](https://github.com/user-attachments/assets/295fc5e7-0907-4f2e-bf3d-83d96ca57a4f)

							Navigating to the Badpath

![Screenshot 2024-09-16 at 10 52 23 AM](https://github.com/user-attachments/assets/46169942-15ea-4de6-84f2-012417bb5a91)


							Creating Rule to Deny Badpath:

![Screenshot 2024-09-16 at 10 53 26 AM](https://github.com/user-attachments/assets/09ae90ae-a254-4b0e-8b6a-764ce24536d6)

![Screenshot 2024-09-16 at 10 53 41 AM](https://github.com/user-attachments/assets/ac891319-dcbf-42b5-b5a9-60f0e6fbe7c9)

							Testing New Rule for Badpath

![Screenshot 2024-09-16 at 10 54 19 AM](https://github.com/user-attachments/assets/b73aa5be-60e5-4eea-9477-f73a8b6eb1bd)

							Testing New Rule for Goodpath

![Screenshot 2024-09-16 at 10 54 50 AM](https://github.com/user-attachments/assets/ab264f6c-84da-4450-b58c-f97613bde038)








