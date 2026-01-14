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


## **Step 3.3: Generate application `z.trvl.ui.00` (Manage Travel) using OData `/DMO/UI_TRAVEL_D_D_O4`**
1. webapp > annotations > `annotation.xml`
2. webapp > `manifest.json`

