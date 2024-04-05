# Steps to follow:

1. Run the following command:

```
yarn install
```

2. Create an "uploads folder"

```
mkdir uploads
```

Once the folder has been created, upload your preferred image and rename it to "image.png"

3. Generate a test wallet for demo purposes. Run the following command:

```
yarn wallet
```

4. Request for airdrop by running the following command:

```
yarn airdrop
```

> Recommended: Import your newly created wallet to Phantom/Solflare with private keys. To get the private key, run the following command: yarn decode 5.

5. Login to Quicknode Dashboard and retrieve API key, and paste it in app.ts file

   > const QUICKNODE_RPC = "paste_api_here";

6. Mint NFT by running the following command:

```
yarn app
```
