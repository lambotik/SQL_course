# SQL_course
### 1. Type in command line: ```git clone https://github.com/lambotik/Software_with_SQL_and_Python.git```
### 2. Type in command line:```cd Software_with_SQL_and_Python```
### APP exchanger_software:
Discription:

Simulates the operation of a currency exchanger. The user is prompted:
1. Select the currency he wants to exchange.
2. Select the amount he wants to exchange.
3. Select the currency for which he wants to exchange.
After that, he is provided with a report on the operation.
The updated data is entered into the database.

- To start exchanger_software.py
    - Type in command line: ```python exchanger_software.py``` and press ```ENTER```
    ### Test data:
  ### Exchange rates:
  
  1 USD = 70 RUB
  
  1 EUR = 80 RUB
  
  1 USD = 0.87 EUR
  
  1 EUR = 1.15 USD
  
  ### Available funds on the user's account:
    
  - RUB: 10000
  - USD: 980
  - EUR: 1017
      
### APP registration_authorization_recovery_password:
Disription:

Prompts the user to select one of the available options:

1. Registration - registration of a new user with entering data into the database.

2. Authorisation - authorization of a previously registered user.

3. Password recovery - password recovery by code.

- To start registration_authorization_recovery_password.py
  - Type in command line ```python registration_authorization_recovery_password.py``` and press ```ENTER```.
    APP created database with test data:
    ### Test data:
    - Login: Ivan
    - Password: qwer1234
    - Recovery code: 1234
   - After type in command line ```python registration_authorization_recovery_password.py``` and press ```ENTER``` to test sofware.
     
### APP atm:
Discription:

This application simulates the operation of an ATM. The user enters the card number, pincode, if this user is in the database, then he is prompted to perform operations of his choice:
1. Show balance information.
2. Withdraw money.
3. Deposit money.
4. Finish work.
5. Transfer money.
   
After successful completion of the transaction with cash flow on the account, the data is updated in the database and entered into the generated report in .csv format.

- To start atm.py
   - #1 Type in command line: ```cd sql_atm``` and press ```ENTER```.
   - #2 Type in command line: ```python atm.py``` and press ```ENTER```.
     ### Test data:
     - card_1_number: 1234, pin_code: 1111, money: 10000
     - card_2_number: 2345, pin_code: 2222, money: 10000
       
### APP Mobile operator:
Discription:

The user enters the billing period, and the application shows the balance on the user's account, if the user does not have enough funds, then the status of his Activity becomes No and the funds are no longer debited.

- To start mobile.py type in command line ```cd mobile_operator``` and press ```ENTER```.
  - #1 Type in command line: ```python mobile.py``` and press ```ENTER```.
    ### Test data:
      - Name: User1, Money: 10000, Tarrif: VIP (1000 per month), Activity: Yes.
      - Name: User2, Money: 10000, Tarrif: Premium (1500 per month), Activity: Yes.
      - Name: User3, Money: 10000, Tarrif: Standard (500 per month), Activity: Yes.
        
### APP Mobile debit:
Dicsription:

Simulates making one call to a randomly selected operator for 30 days, the duration of each call is randomly from 1 to 10 minutes. Writes off funds from the account after each call and shows the full balance.
Generates a report in .csv format about calls made.
    
- To start mobile_month_cycle.py type in command line ```cd mobile_debit``` and press ```ENTER```.
  - #1 Type in command line: ```python mobile_month_cycle.py``` and press ```ENTER```.
    ### Test data:
    - Name: User, Money: 500.
      - Operators:
          - Mts_Mts rate: 1 rub.
          - Mts_Tele2 rate: 2 rub.
          - Mts_Yota rate: 3 rub.

  
