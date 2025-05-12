# dockerAssignment

I created a simple project that displays "this is a sample text for docker assignment - livanshu" using flask and wrote following code in app.py file

![{22E7D432-58B2-4027-980F-88A1A9726E39}](https://github.com/user-attachments/assets/b5673bf6-af08-41e2-b807-c07c27a24898)

I also added the requirements in a file.

![{D2112D62-211B-4302-85C6-86847580C837}](https://github.com/user-attachments/assets/f21e5cfa-548f-43a9-bdb4-e170772403c6)

Then I build the image using  docker build -t livanshuminfy/docker-assignment .

![{C8036075-77C2-4643-8197-E5C568A3C9FC}](https://github.com/user-attachments/assets/6ac83963-9e21-4156-827f-0fd495a07d26)

then i tried running the docker container using docker run -p 5000:5000 docker-assignment 

![{A4ACD9B2-08DD-4D37-A9BC-55E34CD80D73}](https://github.com/user-attachments/assets/7ed9baba-1e88-465a-894a-2f65c28a62c1)

then I pushed into docker registry using docker push livanshuminfy/docker-assignment

![{DACDE7C5-9678-49C6-B756-6B995998E772}](https://github.com/user-attachments/assets/0cce1de2-bc11-41f9-ad52-7be5149ae0da)

-----------------------------------------------------------------------------------------------------------------------------

To pull the image use -->
docker pull livanshuminfy/docker-assignment

after pulling the image run -->
docker run --rm -p 5000:5000 livanshuminfy/docker-assignment

and open the given link in browser search bar -->
http://localhost:5000/

![{D906ECA4-F22D-403F-BB33-E69513C2C664}](https://github.com/user-attachments/assets/2c1e63bb-175d-406d-ad7a-d913c14c79f9)
