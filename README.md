# 🔐 Loan Management System using Hyperledger Fabric

## 🧩 Problem Statement

Traditional loan management systems suffer from multiple inefficiencies and risks:

- ❌ Centralized databases vulnerable to unauthorized access or tampering  
- ⚠️ Lack of transparency and trust between borrowers and lenders  
- 🐢 Difficulty in tracking and updating loan information in real time  
- 📝 Manual verification processes that increase time and operational costs  

These issues lead to data breaches, loan disputes, processing delays, and overall inefficiency.

---

## 🎯 Project Objective

To build a **blockchain-powered Loan Management System** using **Hyperledger Fabric** that:

- Stores loan data securely on an immutable, tamper-proof ledger  
- Enables transparent and auditable transactions between stakeholders  
- Supports **real-time updates** to loan amounts and interest rates  
- Promotes **automation, trust, and traceability** in financial services  

---

## 🛠️ Technologies Used

| Technology         | Description                                 |
|--------------------|---------------------------------------------|
| Hyperledger Fabric | Permissioned blockchain framework           |
| Java Chaincode     | Business logic for loan management          |
| Fabric CA          | Identity and certificate authority          |
| Java SDK           | Client-side interaction with the blockchain |
| CouchDB            | State database for storing loan records     |
| Practical Lab      | Development environment for testing         |

---

## 🔁 Chaincode Functionalities

Implemented in `LoanContract.java`:

1. **`initLedger()`**  
   - Preloads the ledger with sample loan data

2. **`registerLoan(id, borrower, amount, interestRate)`**  
   - Registers a new loan on the blockchain

3. **`readLoan(id)`**  
   - Retrieves loan details by loan ID

4. **`updateLoanAmount(id, newAmount)`**  
   - Updates the loan amount

5. **`updateInterestRate(id, newInterestRate)`**  
   - Updates the interest rate for a loan

---

## 🗂️ Workflow Summary

1. ✅ Admin initializes the ledger with sample data  
2. 📝 New loans are registered via smart contract  
3. 🔄 Loan data is updated when required  
4. 🔍 Authorized users retrieve real-time loan information  

All transactions are recorded immutably on the blockchain, ensuring trust and auditability.

---

## 🏗️ Hyperledger Fabric Architecture

- **Peers** – Host chaincode and maintain the ledger  
- **Orderer** – Packages transactions into blocks  
- **Certificate Authority (CA)** – Manages identities and access  
- **Chaincode** – Defines the loan business logic  
- **Ledger (CouchDB)** – Stores current loan state and block history  

---

## 🌟 Features and Benefits

| Feature                  | Benefit                                           |
|--------------------------|---------------------------------------------------|
| 🔐 Immutable Ledger      | Prevents unauthorized data modification           |
| ⏱️ Real-time Updates     | Ensures accurate and current loan information     |
| 🧾 Paperless Automation   | Reduces human error and manual effort             |
| 🔐 Role-based Access     | Secure access for authorized users only           |
| 🔍 Query Support         | Fast loan lookups using loan ID                   |

---

## ✅ Testing & Verification

- ✅ Chaincode tested using both **Java SDK** and **Fabric CLI**  
- ✅ Peer logs and **CouchDB** states validated after each transaction  
- ✅ Verified core functions: `registerLoan`, `readLoan`, `updateLoanAmount`, `updateInterestRate`  

---

## 🧾 Conclusion

This blockchain-based Loan Management System:

- Demonstrates a **real-world use case** of blockchain in finance  
- Ensures **secure, efficient, and transparent** loan operations  
- Enhances **data integrity**, reduces fraud, and builds trust  
- Acts as a foundational model for future blockchain fintech applications  

---

## 📁 Repository Structure (Optional)


