# MicroBank

MicroBank is a simple program that reads in a series of transactions from a file and calculates the balance of a bank account.

the `input.data` file might look like this

1/10/2026, deposit, 100.00
1/11/2026, withdrawal, 50.00
1/12/2026, deposit, 75.00
1/13/2026, withdrawal, 25.00
1/14/2026, deposit, 24.00
1/15/2026, withdrawal, 10.00
1/16/2026, deposit, 50.00
...

Unlike Payroll, you have to figure out how to read in the data and manage the transactions.

As you're reading them in, be making adjustments to the account balance.
At the end of the list of transactions, print out the final balance.

So, the above example of `input.data` file might end up having an account balance of `134.00`

the pseudocode might looks like this:

```
// open file
// read file line by line
// split line into date, type, amount
// if type is deposit, add amount to balance
// if type is withdrawal, subtract amount from balance
// once you run out of transactions, print final balance
```

Start small, reading in the data.
Then add the logic about what to do depending on whether the transaction is a deposit or withdrawal.
Then add the arithmetic to calculate the running balance.
