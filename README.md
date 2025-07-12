# UPI-Data-Analysis


This repository contains the dashboards and code for analyzing UPI transaction data. The analysis includes various aspects such as transaction volumes, user demographics, transaction success rates, and common transaction patterns.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Columns Description](#columns-description)
- [Dashboards](#dashboards)
  - [Transaction Volume Analysis](#transaction-volume-analysis)
  - [User Demographics](#user-demographics)
  - [Transaction Success Rate](#transaction-success-rate)
  - [Common Transaction Patterns](#common-transaction-patterns)
- [Setup Instructions](#setup-instructions)

## Project Overview

The goal of this project is to perform a comprehensive analysis of UPI transaction data to identify trends and patterns that can help in optimizing payment processes, enhancing user experience, and improving fraud detection mechanisms.

## Data Source

The data used for this analysis was sourced from historical UPI transaction records. The dataset includes various fields that capture different aspects of the transactions.

## Columns Description

- **TransactionID**: Unique identifier for each transaction.
- **TransactionDate**: Date and time of the transaction.
- **Amount**: Transaction amount.
- **BankNameSent**: Name of the bank from which the transaction was sent.
- **BankNameReceived**: Name of the bank that received the transaction.
- **RemainingBalance**: Remaining balance after the transaction.
- **City**: City where the transaction was made.
- **Gender**: Gender of the user.
- **TransactionType**: Type of transaction (e.g., payment, refund).
- **Status**: Status of the transaction (e.g., success, failure).
- **TransactionTime**: Time of the transaction.
- **DeviceType**: Type of device used for the transaction (e.g., smartphone, tablet).
- **PaymentMethod**: Method of payment (e.g., UPI, debit card).
- **MerchantName**: Name of the merchant involved in the transaction.
- **Purpose**: Purpose of the transaction.
- **CustomerAge**: Age of the customer.
- **PaymentMode**: Mode of payment (e.g., QR code, mobile number).
- **Currency**: Currency of the transaction.
- **CustomerAccountNumber**: Customer's account number.
- **MerchantAccountNumber**: Merchant's account number.

## Dashboards

### Transaction Volume Analysis

- **Purpose**: Analyze the volume of transactions over time.
- **Key Visuals**:
  - Monthly transaction volumes
  - Daily transaction trends
  - Peak transaction times

### User Demographics

- **Purpose**: Examine the demographics of users making transactions.
- **Key Visuals**:
  - Age distribution of users
  - Gender distribution
  - Regional distribution of transactions

### Transaction Success Rate

- **Purpose**: Investigate the success rate of transactions.
- **Key Visuals**:
  - Success rate trends over time
  - Factors affecting transaction success
  - Common failure reasons

### Common Transaction Patterns

- **Purpose**: Identify common transaction patterns and behaviors.
- **Key Visuals**:
  - Frequency of different transaction types
  - Popular transaction purposes
  - Common transaction amounts

## Setup Instructions

1. **Clone the Repository**
   ```bash
   https://github.com/Mrigendra488/UPI-Data-Analysis

Data Preparation

* Ensure you have access to the dataset.
* Load the data into Power BI using the provided dataset.

Run Power BI Reports

* Open the Power BI files in Power BI Desktop.
* Ensure all data connections are correctly configured.
* View and interact with the dashboards.
