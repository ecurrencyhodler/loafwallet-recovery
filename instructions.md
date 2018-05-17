This is a guide that will help you recover your litecoins from loafwallet.

#What you need

1. Seed keys
2. Computer
3. The ability to disconnect from the internet for security purposes.
4. [Electrum-ltc](https://electrum-ltc.org/)

#The Steps

1. Click on "Clone/download". You can choose zip or desktop.  I chose zip.  
2. Turn off your wifi or access to the internet.
3. Open the bip-standalone.html file.  It should appear on your browser.
4. Paste/type in your seed keys in the "Enter Paper Key" section.
5. A list of addresses should appear.
6. Look for the addresses you sent your litecoins to.  Copy and paste that onto a doc.  Same with your private keys.  
9. If you can't find your address in step #6, set the "Client" section LoafWallet (Change) and it should list your change addresses and follow through with step #6.
10. Close the standalone .html web page and turn on your wifi.
11. Open Electrum-ltc.  Go to Wallet-> Private Keys-> Sweep.
12. Input the private key and an LTC address you want to send it to. Electrum-ltc autofills one for you.

You now have access to your litecoins.  Don't send the back into your loaf wallet until the bug is fixed.  You can keep them in electrum-ltc or a different wallet.

*Edit:*

If Electrum says "Transaction unrelated to your wallet" create a seedless wallet using the private key and send the funds from there manually.
