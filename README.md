### Introduction
This repo contains the following:
* A simple demo NFT site to demonstrate how someone who holds our credit card could make a purchase of an NFT without gas using MetaMask. 
* Point of Sale (PoS) Android app to allow registered merchant to use this app to accept remittance requests - under `android_pos` folder.
* It does not contain our payment gateway and backend/frontend website interface as those are proprietary, sorry. 

### Point of Sale (POS) Android App
This demo supports the MetaMask wallet mobile app. Here's a demo video - https://youtu.be/IXdMPnaFx9g?t=92

You may install the `Merchant.apk` file under `android_pos` folder on your Android phone (for Android version 4.5 and above). After installation, you'd need to enter your merchant details. But you'd need to sign up as a merchant before being able to use this app. But since this is a just a demo, the merchant signing-up process is not yet available. So, you may use the sample settings below:
*   Merchant name: Eastasia Restaurant
*   Merchant ID: 52
*   Currency: CUSD
*   API Key: 1234

After entering the settings, you'd be able to enter the amount you wish a customer to pay and the app will generate the corresponding QR code. Scan the QR with the MetaMask QR reader on another phone and it should redirect you to the MetaMask in-app browser where you can confirm the payment by making a signature. The signature is verified at the backend.

