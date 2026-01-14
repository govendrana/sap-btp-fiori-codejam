# Step 3: Create Fiori App in SAP Business Application Studio

This section explains how to create a new SAP Fiori application using SAP Business Application Studio.

## **Step 3.1: Open SAP Business Application Studio and Login to Sub Account**
## **Step 3.1.1: Open SAP Business Application Studio**
1. Log in to [SAP BTP Cockpit](https://cockpit.hanatrial.ondemand.com/trial/ and Subscriptions**.
2. Open **SAP Business Application Studio** from Instances and Subscriptions

## **Step 3.1.2: Create a New Dev Space and Login to Sub Account**
1. **Click on Create a New Dev Space**.
   <img width="1910" height="948" alt="image" src="https://github.com/user-attachments/assets/dffcdc0a-181c-4d3f-bd8d-e53e3f0cc1d9" />
2. **Click on created Dev Space (e.g., myFioriSpace_0114 )**   
   <img width="1896" height="336" alt="image" src="https://github.com/user-attachments/assets/6d9f6d44-a523-4eb2-856a-ff69806d6a48" />
3. **Landing Page**
   <img width="1919" height="987" alt="image" src="https://github.com/user-attachments/assets/a34c95c5-139a-45ae-b4b6-bc38b1364ff9" />
4. **Login to Sub Account - Open Terminal**
   <img width="1263" height="588" alt="image" src="https://github.com/user-attachments/assets/f1e06aab-816f-4c5f-9416-73692c2e2bec" />
5. **Type 'cf login --sso / cf login' and provide the API EndPoint e.g., 'https://api.cf.us10-001.hana.ondemand.com'**
   <img width="1287" height="174" alt="image" src="https://github.com/user-attachments/assets/e1b71cf0-feae-4796-9531-12327f348f2e" />
   **API EndPoint: Under Cloud Foundry Environment section in trail account**
   <img width="1275" height="63" alt="image" src="https://github.com/user-attachments/assets/2a00b102-c435-443a-a217-21dce6314e93" />
   **Provide the temporary Authentication Code to login - Open it in your browser, log in with your SAP credentials, and copy the passcode back into the terminal**
   <img width="1302" height="285" alt="image" src="https://github.com/user-attachments/assets/6d573efd-a156-48e5-8216-b2a11fb04e15" />

## **Step 3.2: Generate application `z.trvl.ui.00` (Manage Travel) using OData `/DMO/UI_TRAVEL_D_D_O4`**
1. **File->New Project from Template->SAP FIORI Generator->Select List Report Page**
   <img width="1556" height="891" alt="image" src="https://github.com/user-attachments/assets/43ba2caa-bd83-42c1-b56a-aa7e8ea3e4a1" />
2. **Connect to the System and Select the service /DMO/UI_TRAVEL_D_D_O4**
   <img width="1572" height="885" alt="image" src="https://github.com/user-attachments/assets/cd7eea3b-897c-404b-bd58-6ebd7f7f4d0a" />
3. **Select Main Entry as Travel and Navigation Entry as _Booking**
   <img width="1572" height="891" alt="image" src="https://github.com/user-attachments/assets/025f1f86-266e-418f-b9f0-42c47d48bc0c" />
4. **Provide the Application Details and Generate it**
   <img width="1602" height="897" alt="image" src="https://github.com/user-attachments/assets/fbcb07ce-b27a-4bee-b1a0-6a6aca88ebc1" />
5. **Open the folder /home/user/projects/ to open the application z.manage.travel.00**
   <img width="1862" height="906" alt="image" src="https://github.com/user-attachments/assets/70e6df4a-1db9-4b97-a554-e6e82804c9fb" />
6. **Preview Application: Application Info->Preview Application->Select start-noflp**
   <img width="1571" height="912" alt="image" src="https://github.com/user-attachments/assets/28d5c0e5-3425-4b4e-96f9-2d18670b5b9e" />
7. **Click localhost after server started http://localhost:8082. Then click on Index to launch Application**
   <img width="1911" height="987" alt="image" src="https://github.com/user-attachments/assets/3520d56e-1cf9-4d7e-bf55-a03d43ac8a7f" />
   
## **Step 3.3: Back up to Local Machine
1. webapp > annotations > `annotation.xml`
2. webapp > `manifest.json`
   <img width="1056" height="189" alt="image" src="https://github.com/user-attachments/assets/4006e22f-8833-4748-8bfa-48f322191d52" />

## **Step 3.4: Fiori tools activity**
## **Step 3.4.1: Gloabl WORK IN PROGRESS **
## **Step 3.4.1: Travel List Page <WORK IN PROGRESS> **


