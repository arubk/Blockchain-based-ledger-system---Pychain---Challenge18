# Blockchain based ledger system - Pychain - Challenge18

This repository contains the code to build a blockchain-based ledger system, completed with a user-friendly web interface. This ledger allows partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

![18-4-application-image](https://user-images.githubusercontent.com/94565094/163091751-08ed09a4-f00f-4011-8a39-1be0a7875c49.png)

## Technologies

This project leverages python 3.7 with the following packages:

*Pandas - 1.4.1

*Streamlit - 1.8.1

## Installation Guide


     pip install pandas
 
     pip install streamlit
 
## Usage

To use the application, download the repository and run the application with the following command:

       streamlit run pychain.py
     
In case Command Promt shows this message:
     "If you're one of our development partners or you're interested in getting
  personal technical support or Streamlit updates, please enter your email
  address below. Otherwise, you may leave the field blank."
     
     streamlit run pychain.py --server.headless=true
     
## PyChain APP
     Block(record=Record(sender='Sending address', receiver='Receiving address', amount='100'), creator_id=42, prev_hash='04ab8aabd720d1c0d783b5f5bcee073968e47d8c6aab6f39b9d832a91b8b2fe8', timestamp='04:30:13', nonce=200)

![pychain1](https://user-images.githubusercontent.com/94565094/163100687-d74f329d-a9e8-44b8-85d7-f458d1bf842e.png)
     
     Block(record='Genesis', creator_id=0, prev_hash='0', timestamp='04:26:24', nonce=0)
     
![pychain2](https://user-images.githubusercontent.com/94565094/163101148-5a9de170-0775-4858-889b-50faa42a74f9.png)

## Contributors

Project author : A.Rubkevich

Contact information : anastasiyarubkevich@github.com

## License

MIT License

Copyright (c) 2022
