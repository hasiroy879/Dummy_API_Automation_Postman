
## Creating Postman Collection on dmoney REST API by using postman 

#### Description: By doing this project, I can create postman collection on the following test cases and I also create some positive & negative test cases in a standard test case format for the dmoney REST API.
- Admin creates an Agent, 2 random Customers, and a Merchant.
  Admin email: admin@roadtocareer.net / Pass: 1234
- Deposit some money from the SYSTEM account to the Agent.
  System account: SYSTEM (range 10 TK to 10,000 TK)
- Agent deposits money to one of the Customers.
  Hint: from Ac: Agent, to Ac: Customer
- Check the Agent's balance.
- Then, send money from one Customer to another Customer.
  Hint: from Ac: Customer, to Ac: Customer
- Withdraw any amount from a Customer to the Agent (range 10 TK to 10,000 TK).
  Hint: fromAc: Customer, toAc: Agent
- Check the Customer's balance and transaction statement by trnxId.
- Make a payment from the second Customer to the Merchant.
  Hint: from Ac: Customer, to Ac: Merchant
- The second Customer checks both balance and transaction statement.
- The Merchant checks his balance.
- 
#### The api documentation link
[Click here](https://l.facebook.com/l.php?u=https%3A%2F%2Fdocumenter.getpostman.com%2Fview%2F39893426%2F2sB2jAaSx1%3Ffbclid%3DIwZXh0bgNhZW0CMTAAYnJpZBExWG1RTlBFaXNXZzhsTGVwaAEe7EAjpI9Q8PXs8dTdOtZvyt1oJB_kjUOrH6LUrqmUGdHaUpLztMxHYAJ1yRE_aem_yVGVJxNbHy0KZlqaK_2zlw&h=AT1cziRHT1W-cZTejgMYLD4IG31CVQLt6jAwrtGcExUPesqqiwA42sxnTMppam_oA6uhDj29GRcl7h1dVHYEJyMX4V4yFON-zK3e7QJ6jYts9eih05kYyDduX4vbQ-Piy_-nOw)

#### Technology I used:
- Postman
- Report: Newman report
- 
#### Newman report
![image alt](https://github.com/hasiroy879/Dummy_API_Automation_Postman/blob/main/dmoney.png?raw=true)

#### Test cases link
[Click here](https://l.facebook.com/l.php?u=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1maIFjeB-W_wAslsM0ITNFZKSU8POEZnn%2Fedit%3Fusp%3Ddrivesdk%26ouid%3D108828473512528251679%26rtpof%3Dtrue%26sd%3Dtrue%26fbclid%3DIwZXh0bgNhZW0CMTAAYnJpZBExWG1RTlBFaXNXZzhsTGVwaAEeLO-Xjub0SAvqhk91fiz69aYhKvy-5squm428kpfSsBMRhM3TmZ7zSn-1LpU_aem_ZzNxUlzl73gq1XSkCBOMOw&h=AT3REcB4PQUGGH_2qRbYCs0OHJB2k9NdCBZpdO5lmM1JMRNYtFyNcdgUt_PW9_U-LlQ19xwNVd2bVI2-WIi_IC4UMBhl5fvS6o1C4mcuZKeJ5mTGFX29fq1TTfk_PdEabjBTaQ)
