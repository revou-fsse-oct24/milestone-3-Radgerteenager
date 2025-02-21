[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/OEA-wQat)

# 📌 RevoBank Activity Diagram

This repository contains the **User Authentication** and **Transaction Handling** activity diagrams for **RevoBank**.

---

## **🛠 User Authentication Process**
The **User Authentication** process ensures secure access to the RevoBank system. It follows these steps:

1. **Enter Credentials** – The user inputs their username and password.  
2. **Validate Credentials** – The system verifies if the provided credentials match the stored data.  
3. **Retry Login** – If the credentials are incorrect, the user must retry.  
4. **Success Check** – If validation is successful, the system proceeds.  
   - ✅ **Successful Login** – The user gains access to the system.  
   - ❌ **Failed Login** – The user must retry entering valid credentials.  

---

## **💰 Transaction Handling Process**
The **Transaction Handling** workflow ensures secure money transfers and account balance validation.

### **1️⃣ Checking Balance Before Transaction**
1. **Initiate Transaction** – The user starts a transaction (withdrawal, transfer, etc.).
2. **Check Balance** – The system verifies if the account has sufficient funds.
3. **Sufficient Funds?**  
   - ✅ **Yes** → The system processes the transaction.  
   - ❌ **No** → The transaction is **canceled** due to insufficient funds.  

### **2️⃣ Saving or Transferring Money**
1. **Save Money** – The user chooses to deposit or transfer money.
2. **Money Count** – The system calculates the amount to be processed.
3. **Save to Account or Send to Another Account**  
   - ✅ **Save to Account** → The system updates the balance.  
   - 🔄 **Send to Another Account** → The system validates recipient credentials before completing the transfer.  
4. **Check Balance & Confirmation** – The system verifies and confirms the transaction as **successful**.  

---

## **🖼 Activity Diagram**
![Activity Diagram] (https://raw.githubusercontent.com/revou-fsse-oct24/milestone-3-Radgerteenager/refs/heads/main/Revo%20Bank%20Activity%20Diagram.jpg?token=GHSAT0AAAAAAC5DLX5UFO5Z26QE6FVKV324Z5YVPOA)


---


