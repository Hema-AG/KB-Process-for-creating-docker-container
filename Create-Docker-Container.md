### Disclaimer: Before starting to build a container ensure you have docker app open in your desktop

#### Steps to build a container:
1. Click on the >< sign at the bottom left of VSCode home page
<img width="204" height="122" alt="image" src="https://github.com/user-attachments/assets/433d60ed-cad0-421e-9544-64734f3dea9b" />

2. Click on "New Dev Container"
<img width="869" height="138" alt="image" src="https://github.com/user-attachments/assets/b8c080ff-df3f-4734-bcfa-1a24c77d44d4" />

3. Search for "Python 3"
<img width="815" height="153" alt="image" src="https://github.com/user-attachments/assets/77bf4c68-7883-404e-9c12-76a53aa479b3" />

4. Click on "Create Dev Container"
<img width="826" height="178" alt="image" src="https://github.com/user-attachments/assets/cc50a67b-5c92-4c25-92fc-bd05af47d612" />

5. Container is created when you can see your JSON file
<img width="321" height="83" alt="image" src="https://github.com/user-attachments/assets/de14c897-a21c-4fba-a23c-f2e539fad3de" />

6. Open your devcontainer.json file to configure your conatiner according to your needs
<img width="1075" height="618" alt="image" src="https://github.com/user-attachments/assets/449307d4-6689-4845-a690-3fe69518990c" />

7. You can uncomment the postCreateCommand line to run pip intall -r requirements.txt automatically
<img width="1056" height="637" alt="image" src="https://github.com/user-attachments/assets/df4e6f33-5b36-4035-8f5c-eaa6dbf5d6f9" />

8. Click on the bell icon to check notifications and click "Rebuild" to rebuild your container with the changes made
<img width="621" height="254" alt="image" src="https://github.com/user-attachments/assets/d52c1065-de96-4c1e-8a77-74e9c7918cf1" />

Ps: This method only creates a devcontainer.json file. You can create a Dockerfile seperately if required.
