# voidcoin
Cryptocurrency using blockchain. No predefined blockchain is used.


## we created three dummy user with web socket.

to run we have to start the server in three different terminal
** Please use bash if working on window**

to create first user 

npm run dev

to create second user run
HTTP_PORT=3002 P2P_PORT=4002 PEERS=ws://localhost:4001  npm run dev

to create third useer run
HTTP_PORT=3003 P2P_PORT=4003 PEERS=ws://localhost:4001,ws://localhost:4002  npm run dev


