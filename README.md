# MQL-CopyTrade

Copy Trade System for MetaTrader 4/MetaTrader 5 Client based on MQL script.

![GitHub](https://img.shields.io/github/license/jiowcl/MQL-CopyTrade.svg)
![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/dingmaotu/mql-zmq.svg)

## Environment

- Windows 7 above (recommend)
- MetaTrader 4 Client / MetaTrader 5 Client  
- [ZeroMQ](https://github.com/zeromq)  
- [ZeroMQ for MQL](https://github.com/dingmaotu/mql-zmq)  

## Features

- Remote Publisher and Subscriber (Based on IP address)  
- New Order (Market Order, Pending Order)  
- Modify Order (TP, SL)  
- Close Order (Normal Close, Partial Close)  
- Custom Trading Symbol between Publisher and Subscriber  
- Subscriber Copy From Multi-Publisher  
- Subscriber Min Lots, Max Lots and Percent Lots  
- Subscriber Invert Original Orders  
- Subscriber Symbol adjust  
- Subscriber Free Margin Check  

The Publishers do not need to log in with a trading password, just log in and using the investor password.  

## License

Copyright (c) 2017-2021 Ji-Feng Tsai.  
Copyright (c) 2022.. TradingDemon & DAppIT
MQL-Zmq Copyright (c) Ding Li [ZeroMQ for MQL](https://github.com/dingmaotu).  

Code released under the MIT license.

## Extended / Improved

- Print / Alert messages
- Ability to recalculate lots at client side with clientEquity / publisherEquity ratio and with a multiply factor

## TODO

- Set TP's at client side same as publisher when trailing trades at publisher are created, now only new trade gets same TP as publisher

## Donation

If this application help you reduce time to trading, you can give me a cup of thee :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/donate/?hosted_button_id=85P2F2W7D8VCA)

[Paypal Me](https://paypal.me/dAppITNL?locale.x=nl_NL)