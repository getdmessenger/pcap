# PCAP
The Private Chat Authentication Protocol, is what allows one users to request a one-to-one private chat with another user within dMessenger. Users authenticate each other's dWebID (via dWeb's (UserSwarm) [https://github.com/dwebprotocol/uswarm.git)) and then exchange a seed which is used to encrypt their conversation. Conversations are distributed within a [dAppDB](https://github.com/dwebprotocol/dappdb) over dweb://, but all data within the database is completely encrypted using the exchanged seed.

## Install
npm install @dmessenger/pcap

## API 
Coming soon!

## Example Usage
You can find example usage within dMessenger's [Controller](https://github.com/getdmessenger/dmessenger-desktop/blob/master/Controller.js).