# n2d-Lottery
Lottery game using chainlink VRF.


# How to run

Navigate to the nextjs "lottogame" project front-end folder and install dependencies.

```shell
cd lottogame
npm i 
```

Update the config.js file located in the "components" folder with your contract addresses: 

```shell
export const lotterycontract = 'ADD-LOTTO-SMART-CONTRACT';
export const erc20contract = "ADD-ERC20-SMART-CONTRACT";
```

CTRL + S to save file

Update the interfaces.js file located in the "components" folder with your backend addresses: 

```shell
const backend = 'http://ADD-BACKEND-IP-ADDRESS:8082'
```

CTRL + S to save file

Run the Lotto Game Front-end:

```shell
cd lottogame
npm run dev
```

Confirm you can access the front-end!


