# ATM Simulator in C
## Description
This is a simple ATM simulator in C. It is a console application that allows you to perform the following operations:
- Check balance
- Deposit
- Withdraw
- Change PIN

## How to run
- Clone the repository
For Linux:
```bash
make -f atm.mk
./atm
```
For Windows:
```bash
mingw32-make -f atm.mk
atm.exe
```

## How to use
On execution, There are 3 options:
- Create a new account
- Login to an existing account
- Exit

### Create a new account
Select the first option by entering 1 and press enter. You will be prompted to enter the following:
- Enter your name
- Enter your PIN
- Enter your secret question and answer to that question

### Login to an existing account
Select the second option by entering 2 and press enter. You will be prompted to enter the following:
- Enter your name
- Enter your PIN

If the name and PIN are correct, you will be logged in and you will be able to perform the following operations:
- Check balance
- Deposit
- Withdraw
- Change PIN

Or if the name and PIN are incorrect, you will be prompted to enter the name and PIN again.

The secret question and answer are used to recover your account if you forget your PIN. If you forget your PIN, you will be prompted to enter the following:
- Enter your name
- Enter your secret question and answer to that question

If the name and secret question and answer are correct, you will be prompted to enter the following:
- Enter your new PIN

If the name and secret question and answer are incorrect, you will be prompted to enter the name and secret question and answer again.

### Exit
Select the third option by entering 3 and press enter. The application will exit.