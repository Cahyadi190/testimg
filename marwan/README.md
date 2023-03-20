### Install dependencies

- [NodeJS](https://nodejs.org/en/)

- NPM

- GIT

```
curl http://deb.nodesource.com/setup_lts.x | sudo bash -
sudo apt install git nodejs -y
```

### Clone
```
git clone https://github.com/Cahyadi190/inery-testnet-faucet-tasks.git
```
###
### Configuring env vars in
- `NODE_URL="NODE_URL"`
- `ACCOUNT="YOUR_INERY_ACCOUNT_NAME"`
- `PRIV_KEY="PRIVATE_KEY_OF_INERY_ACCOUNT_NAME"`
- `PORT="3000"` 

```
cd inery-testnet-faucet-tasks/marwan
```
### Install module dependencies

```
npm install
```

## Run the server
```
node inery.js
```
