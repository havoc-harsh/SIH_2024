# IMP: This was migrated here from gitLab ,orignal repo was made private by SIH officials on gitlab
**Slightly better version in leftversion branch** 

# CryptTrail
CryptTrail is a web platform enabling security officials to deanonymize P2P Web3 transactions using a pre-trained AI model that detects suspicious symptoms. This tool is designed to help prevent money laundering and the flow of black money by identifying illicit transaction patterns and flagging them for further investigation.

## Table of Contents

- [Installation](#installation)
- [About SIH 2024](#sih2024)
- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)


# To set up the project locally
The project consists of two interconnected parts: a next app: CryptoSIH and a flask AI Model powered application : ml . 
Clone the repo and run npm install inside CryptoSIH , run pip install inside ml .
Run Next App locally by running npm run dev in Crypto SIH terminal, and python app.py in ml terminal .
Now you're ready to experience the app

# About SIH2024 
Organized by the Ministry of Education’s Innovation Cell (MIC), SIH 2024 is the biggest hackathon in India with a NationWide Participation .
Team Participation: More than 86,000 teams participated at the institute level, comprising over 5,16,000 students
Grand Finale: Over 1,300 student teams advanced to the Grand Finale of SIH 2024, which was held across 51 nodal centers nationwide. The Software Edition featured a continuous 36-hour coding marathon, while the Hardware Edition spanned from December 11 to 15, 2024

## Overview

In today's rapidly evolving financial landscape, the rise of decentralized transactions poses unique challenges for regulatory bodies and law enforcement. CryptTrail addresses these challenges by combining blockchain data analysis with advanced AI techniques to deanonymize and assess the risk of P2P Web3 transactions. The platform enables security officials to quickly identify suspicious activities, thereby preventing the movement of illicit funds.

## Features

- **Deanonymization**: Leverages a pre-trained AI model to deanonymize transactions on P2P Web3 platforms.
- **Suspicious Activity Detection**: Automatically analyzes transaction patterns and flags potential money laundering activities.
- **Real-time Monitoring**: Provides live updates and notifications for transactions that match suspicious criteria.
- **User-Friendly Interface**: Offers an intuitive dashboard for security officials to monitor and investigate flagged transactions.
- **Enhanced Security & Compliance**: Assists organizations in adhering to anti-money laundering regulations and improves overall transactional security.

## Architecture

CryptTrail is built with a modular architecture consisting of the following key components:

- **Frontend**:  
  - A responsive web interface (built with frameworks like React) that displays transaction data, alerts, and detailed reports.
  
- **Backend**:  
  - A server-side application responsible for fetching transaction data from blockchain networks, processing this data, and interfacing with the AI model.
  
- **AI Engine**:  
  - A pre-trained AI model that evaluates transaction data for suspicious symptoms and patterns.
  
- **Blockchain Integration**:  
  - Connectors that interface directly with various blockchain networks to pull P2P transaction data for analysis.

