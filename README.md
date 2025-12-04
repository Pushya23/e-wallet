# 💰 E-WALLET

## 📌 About the Project
E-Wallet is a backend application for a digital wallet/payment system — built (or intended to be built) using standard server-side technologies. It provides the core server-side logic to manage user wallets, balances, transactions, and payments. This repo serves as the foundation for building a full e-wallet / digital-payment system (mobile or web) by exposing REST APIs that support wallet operations, fund transfers, transaction history, and more.

## 📚Tech stack
* Language: Java (100% according to repo)

* Build Tool: Maven (with pom.xml)

* Framework / ORM: Spring Boot + Hibernate

* Real-time Event Handling: Kafka

* Database: MySQL, Redis

## ✨ Features
* User registration/login and wallet account creation

* Maintain wallet balance per user

* Add funds to wallet (top-up)

* Transfer funds between users (peer-to-peer / wallet-to-wallet transfers)

* Withdraw funds

* View transaction history — each transaction logged with date/time, amount, sender/receiver, transaction type (top-up, transfer, withdrawal, etc.)

* Notifications — e.g. when funds are added, transferred, received, or when account activity occurs

* CRUD operations for user, wallet, transactions (as backend REST APIs)

## 🚀 Future Enhancements
* Integration with bank accounts / cards — to allow adding money from bank or card, and withdrawing from wallet to bank account.

* Full-stack integration: Connecting a frontend (React / Angular / mobile) to this backend for a complete user experience

* Bill payments, merchant payments, and support for QR-code / contactless payments (for real-world payments).

* Real-time transactions and instant fund transfers between users, with proper concurrency & consistency control.

* Spending / expense tracking — letting users review their transactions, filter by date/type/amount for record keeping / budgeting.

* Loyalty / rewards program or cashback / offers for transactions to engage users.

* Support for recurring payments, bill auto-payments, or scheduled transfers.
