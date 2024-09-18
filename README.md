# raydium-volume-bot + monitor

Raydium volume bot + Monitor : This bot can proceed buy and sell over and over until token price is over $ XX

## How does it work

This bot is designed to monitor and buy and sell or only buy
Once token value is below $XX , bot runs automatically
You can run bot manually for increase volume
If bot runs automatic way , it keeps buying and selling token until other users buy that token.
And then the price of that token is below $YY , bot stop buying and selling automatically.

## How to start bot

You can start bot with **command line** or just double click on below file

```
    npm run start : run.bat             //  proceed endless buy and sell in every distributed wallet
    npm run gather : gather.bat         //  collect fund from every distributed wallet to main wallet
    npm run status : status.bat         //  track wallet status event such as volume up and down and if condition is satisfied , proceed buy and sell
    npm run massive : massiveBuy.bat    //  proceed only one massive buy in every distributed wallet
```
Addition : If you wanna use Automatic bot , Contact on ME with telegram !!!

## Every CMD Function

#### npm run start

- distribute sol to a number of wallets
- save sub wallets info to file for safty of funds
- proceed buy and sell in every wallets

#### npm run gather

- load wallat data from data.json
- gather funds from every sub wallets

#### npm run status

- get pool info and start monitoring pool and token price
- if condition is satisfied , proceed buy and sell

#### npm run massive

- distribute sol to a number of wallets
- save sub wallets info to file for safty of funds
- proceed only buy in every wallets

## Result


