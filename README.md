# Decentralized Voting (web3-Voting)

A decentralized voting system based on [Ethereum blockchain](https://ethereum.org/dapps/) technology.

## System Workflow

A brief explanation on the basic workflow of the application.

- Admin will create a voting instance by launching/deploying the system in a blockchain network (EVM), then create an election instance and start the election with the details of the election filled in (including candidates for voters to vote).
- Then the likely voters connect to the same blockchain network register to become a voter. Once the users successfully register, their respective details are sent/displayed in the admins' panel (i.e. verification page).
- The admin then will check if the registration information (blockchain account address, name, and phone number) is valid and matches with his record. If yes, then the admin approves the registered user making them eligible to take part and cast their respective vote in the election.
- The registered user (voter) following the approval from the admin casts their vote to the candidate of interest (from the voting page).
- After some time, depending on the scale of the election the admin ends the election. As that happens the voting is closed and the results are displayed announcing the winner at the top of the results page.


  **See demo [here](https://youtu.be/nh1zfTTrdII "Watch dVoting demo").**
  
  ---
  
  ### Requirements

- [Node.js]
- [Truffle]
- [Ganache]
- [Metamask]
