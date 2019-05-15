Xceder is designed for the high frequency and algo trading. It can route the order in millisecond level. In our live trading, 
we see almost all order process latency less than 10 milliseconds, many of them even just 1 millisecond. leverage on this speed edge, 
the spreader trading and algo trading is not just privilege from those big players.

# Project structure

This project is place to hold the material to public. What you can find here is

1. RSA public key for the login

   This is to encrypt the account password MD5 hash code.

2. protobuf message protocol to communicate with xceder trade gateway

   This is how the client side can subscribe the price and submit the orders

3. C# API library to handle the network communication and messages

   This is to simplify the client side development. It will handle the protobuf message protocol and network communication.
   The client side only need call the provided functions to submit the request and receive the real time data through the events
   
4. Algo (EA) scripts 
    
    Algo modules are listed here [algos] (algos)   

# Tutorial

Get started using this step by step [tutorial](https://github.com/xcedertechnology/Xceder/wiki/).

More books are available here http://books.xceder.com

# To use Xceder
* UI
  www.xceder.com
  
* Excel plugin  https://github.com/xcedertechnology/Xceder/releases/ in Excel (2007 above). 

    **For 64bit Excel, you need open the file which name contains '64'**

# Versions

[Change Log](changelog.md)

0.x release: [0.9.9.8](https://github.com/xcedertechnology/Xceder/releases)

@Copyright 2016 [xceder technology](http://www.xceder.com)



