# Project Title: Automating Demo Transaction API Testing using JMeter  
### Project Summary: In this project a flow has been created, where Admin can login using valid credentials for performing CRUD operations. For instance, the Admin can create various roles on the platform such as Agent, Customer and Merchant. In addition, an Agent can deposit money to Customer roles which the Agent role got deposited from the SYSTEM or Admin role. Later, the Customer role can send money to other Customer roles or make payments or send money to Merchant or Agent roles.  

## Prerequisites:  
- jdk(LTS version)
- JMeter

## How to run?
### Execute following commands to generate the HTML report:
- jmeter -n -t <filename.jmx> -l <filename.jtl> -e -o Reports
#### Alternative command: 
- jmeter -n -t <filename.jmx> -l <filename.csv> -e -o Reports

## Documentation:
- User documentation:  
  https://documenter.getpostman.com/view/1844288/2s9YeABaGo
- Transaction documentation:  
  https://documenter.getpostman.com/view/1844288/2s9YeABaGp
## Output
![jmeter-2](https://github.com/zubdotexe/demo-transaction-api-jmeter/assets/64923600/f65c86ec-ea47-4b83-ab88-a9986014a072)

