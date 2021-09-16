###### Problem description - Bank kata

Create a simple bank application with the following features:

- Deposit into Account
- Withdraw from an Account
- Print a bank statement to the console

#### Acceptance Criteria

Statement should have transactions in the following format:

```
> DATE       | AMOUNT    | BALANCE
> 10/04/2014 | 500.00    | 1400.00
> 02/04/2014 | -100.00   | 900.00
> 01/04/2014 | 1000.00   | 1000.00

```

##### Starting point and constraints
1. Start with a class with the following structure:

public class Account {
    public void deposit(int amount);
    public void withdraw(int amount);
    public void printStatement();
}

2. You are not allowed to add any other public method to this class.
3. Use Strings and Integers for dates and amounts (keep it simple)
4. Don't worry about spacing in the statement printed on the console.