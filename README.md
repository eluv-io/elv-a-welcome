
# Welcome to the Eluvio Content Fabric 

The following quick start steps will allow you to create and onboard content administrator accounts in your tenancy.

**Onboarding the Eluvio Content Fabric** 

**FOR THE DEMO NETWORK**
1. Browse to ​https://core.demov3.contentfabric.io

**FOR THE PRODUCTION NETWORK**
1. Browse to https://core.v3.contentfabric.io

**THEN**

2.	Click ​Accounts​, ​Add Account,​ and ​Mneumonic
3.	Click ​Generate Mneumonic. ​Copy the resulting mneumonic displayed for safe keeping. Note: this mneumonic is the only recovery path for your private key and thus you MUST NOT lose it.

![image](https://user-images.githubusercontent.com/30604947/129946672-b57b92c3-b3c1-494b-b6a5-1022ebc89f56.png)

4.	Set the default password (in the Password option) to your desired wallet password. This password secures the local enrypted storage of your private key.
5.	Click ​Submit​. This will display the Account with no name and display a message that the account has insufficient funds. Copy the Address for the account (the long hexadecimal string) and paste into slack/email to Eluvio. Eluvio will add funds.

![image](https://user-images.githubusercontent.com/30604947/129946713-43f13ef4-19d5-41d8-aa3b-a1484612266a.png)

6. After Eluvio has added funds, click ​Profile​ Select the account and click the name box to reveal an option to enter a human readable account name, e.g. your name and save.

![image](https://user-images.githubusercontent.com/30604947/129946803-31d79b47-5975-4ed1-b629-bd4da3f0defb.png)

7. When you want to log in to utilize the Fabric Browser, Video Editor, etc. click the Account Name, and you will be prompted to enter your wallet password set in 3 above to unlock the account​ and you are “logged in”. To switch accounts use the control in upper right corner. Switching effectively locks the previous account’s wallet and unlocks the target next account’s wallet. You will be prompted to enter your wallet passphrase when you do this.


**Overview of Key APIs and Tools**

**Client APIs**
- Start https://eluv-io.github.io/elv-client-js/ElvClient.html for an overview of the client API for publishing, playout, viewing, and minting.
- To publish full length content start here https://eluv-io.github.io/elv-client-js/abr/index.html

**Here are a few particular topics of interest:**

- Streaming https://github.com/eluv-io/elv-stream-sample
- Publishing Content https://eluv-io.github.io/elv-client-js/abr/index.html
- Content Management https://eluv-io.github.io/elv-client-js/#editing

**Other APIs**
- Site Search https://github.com/eluv-io/elv-search
- ML Tagging  https://github.com/eluv-io/elv-tagger
- Bitcode https://github.com/eluv-io/content-bitcode


**Applications** 
Many of our applications are fully open source and can be used as a reference.

- Site Sample https://github.com/eluv-io/elv-site-sample
- Fabric Browser https://github.com/eluv-io/elv-fabric-browser
- Asset Manager https://github.com/eluv-io/elv-asset-manager
- Video Player https://github.com/eluv-io/elv-player-js
- Video Editor https://github.com/eluv-io/elv-video-editor

**Content Fabric Technology**

- Core Technology https://live.eluv.io/technology
- Fabric Blockchain https://live.eluv.io/blockchain
