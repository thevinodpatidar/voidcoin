# voidcoin
Cryptocurrency using blockchain. No predefined blockchain is used.

## We have used Web Socket to create dummy users.

We have to run commands for three times to create three dummy user.

**Please Use bash terminal if using windows**

TO create first user run
```
npm run dev

```
to create second user by running

HTTP_PORT=3002 P2P_PORT=4002 PEERS=ws://localhost:4001 npm run dev

to create third user run

HTTP_PORT=3003 P2P_PORT=4003 PEERS=ws://localhost:4001,ws://localhost:4002 npm run dev


how open in browser...
