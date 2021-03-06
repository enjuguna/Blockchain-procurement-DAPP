# Asili Procurement & Supply Chain System (UNODC Hackathon 2020)
![Asili Logo](https://github.com/enjuguna/Blockchain-procurement-DAPP/blob/master/Asili.png?raw=true)

### This project is built as a solution to the 2020 UNODC Virtual Blockchain Hackathon
## The Problem Statement
In our country today the biggest problem in our economy is corruption which has questioned the reputation of our country and its citizens.
Most of this corruption takes place in the procurement process. 
Finding ways to monitor financial transactions and create transparency in the process will go a long way in controlling the corruption in our country. 
Solution Application of Blockchain in procurement where there are certain applications: 
1. There is the prevention of fraud(fraudulent suppliers) - the absence of the right hash on a certain block 
2. Suppliers are managed - Transparency in the bidding process where there is a record of every transaction 
3. Traceability - Goods can be tracked at every stage of the supply chain 
4. Smart contracts - Are executed only if a certain condition is met 
5. Ledger trust - Multiple levels of verification and ensuring that the customers and suppliers are on the same page. 
6. Financial tracking- All payments are made through the system.

## Presentation Slides : [Here](https://docs.google.com/presentation/d/1FmhQpeytOuIVX-kCDtWUTvJrU5UUP4asUa9c1ojB1os/edit?usp=sharing) 


Us as the Developers shall implement end-to-end process for Procurement and supply chain, which contains steps such as: 

A) Procurement from a vendor </br>
B) Shipping of Items </br>
C) Transportation of items along the supply chain </br>
D) Accceptance at the store  </br>
E) Paying vendors via Smart contracts  </br>

For out implementation we shall be using open source technologies such as web3, remix for deploying smart contracts on the Ropsten test network


## Demo/Explanatory Video: [Here](https://youtu.be/gW_-CeEb3kc)



## Location Description
Once cloned, the Application comes in two parts: Supply Chain and Procurement Side

For procurement: Launch the server in the Procurement directory
For Supply Chain: Launch the server in the Supply Chain Directory


## Running on a Local server
  For this approach, we have used Python
  
  Once you are in the preferred directory, start the server using: 
  
  python -m http.server 1337
  
  You can then start the other part - Supply Chain on a different port, Example:
  
  python -m http.server 1338
  
  Viola! Now you have the application running.
  
  
  ### Smart Contracts
  The smart contracts have been deployed on the Ropsten test network
