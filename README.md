<br />
<p align="center">
  <h3 align="center">Hedera Hashgraph Consensus Service</h3>
</p>



## Table of Contents

* [About](#about)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Contact](#contact)



## About

Testing the [Hedera Hashgraph](https://docs.hedera.com/guides/docs/sdks) Consensus Service. Upload a file using React and an Express server. On upload, a message is submitted to the Hedera Hashgraph network containing the original filename.

Within the Hedera Hashgraph Consensus Service, client applications submit a message (a string of bytes) and give the message a topic (an ID number). This message can include relevant details of a transaction, such as a bid on a financial asset, or in this case, the name of the file. The topic (the ID) will allow messages with the same topic to be classified together. Read more here: [Hedera Hashgraph Consensus Service White Paper](https://hedera.com/hh-consensus-service-whitepaper.pdf).

### Built With

* [React](https://reactjs.org/)
* [Express](https://expressjs.com/)
* [Multer](https://github.com/expressjs/multer)
* [Hedera Hashgraph JavaScript SDK](https://docs.hedera.com/guides/docs/sdks)

## Getting Started

To get a local copy up and running follow these simple steps:

### Installation

1. Sign up for a Testnet account to get an ID and keys from [Hedera](https://hedera.com/).

2. Clone the repo

3. Install the packages
```sh
npm install
```
5. Add your account id and keys in the `server.js` file

6. Start the server
```bash
node server.js
```

7. Start the React frontend
```bash
npm start
```

8. Upload a file

## Contact

Ezra Mizrahi - ezra.mizrahi@hey.com
