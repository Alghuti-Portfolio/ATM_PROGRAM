# ATM_PROGRAM

system.


## Instructions

Read the following user stories for an ATM:

  * As a user of an ATM, I: **input my PIN for identification.**

  * As a user of an ATM, I: **identify whether I’m going to make a deposit or withdrawal.**

  * As a user of an ATM, I: **input the amount of my deposit or withdrawal.**

  * As a user of an ATM, I: **receive cash.**

  * As a user of an ATM, I: **deposit cash and checks.**

  * As a user of an ATM, I: **want to receive my adjusted account balance.**




# Pseudocode User Stories

Here are some examples of pseudocode for the cd user stories:

  * As a user of a cd interface (cdi), I: **input my PIN for identification.**
  ```
  # Import closing disclosure as cd
  # Import data that has usernames and corresponding pins
  # Store it in a Python dictionary
  # Ask the user for their username and store it in a variable
  # Then create a PIN variable and ask the user to input their PIN
  # Look up the PIN associated with the provided username
  # Check to see the true PIN is the same as the entered PIN
  # If it is, proceed to the next part of the program
  # If it isn't, display an error message and prompt the user to try entering the PIN again
  # Give the user a set number of attempts (such as 4) to enter the correct PIN
  # Display the attempt number each time and explain when they will be locked out of their account
  ```

  * As a user of an cdi, I: **identify whether I’m going to make a deposit or withdrawal.**
```
  # Display "deposit or withdrawal" to the user
  # Allow the user to input a selection
  # Make sure the selection is either deposit or withdrawal
  # If the selection is not deposit or withdrawal, display an error message
  # Allow the user to make a correct selection
```
  * As a user of an cdi, I: **input the amount of my deposit or withdrawal.**
```
  # Display text to the user telling them to input an amount, in dollars
  # If the amount is not positive, display an error message
  # Allow the user to try again until there is no error
```
  * As a user of an cdi, I: **receive cash.**
```
  # Confirm that there is enough money in the account to allow withdrawal
  # Subtract the withdrawal amount from the account balance
  # Display a message to the user telling them that they have received cash
```
  * As a user of an cdi, I: **deposit cash and checks.**
```
  # Ask the user if they are depositing cash or checks
  # Ask the user how many checks they are depositing
  # Ask the user which account they would like to deposit the check into
  # Update the balance of the selected account 
  # Display a message to the user that confirms the deposit
```
  * As a user of an cdi, I: **want to receive my adjusted account balance.** 
```
  # Ask the user which account they would like to see
  # Display the account balance
```
