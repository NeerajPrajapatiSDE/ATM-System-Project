## ATM System Project

### Overview

This C++ project implements a simple ATM (Automated Teller Machine) system. The system allows users to create new accounts or access existing ones, perform various banking transactions, and manage their account details.

### Features

1. **Account Creation:** Users can create new accounts by providing their ID, name, age, and gender. The system automatically generates a unique account number and a 4-digit PIN for security.

2. **Transaction Options:** Users can perform multiple banking transactions, including cash withdrawal, checking balance, fast cash options, depositing money, and resetting their PIN.

3. **Security Measures:** The system incorporates security measures such as a 4-digit PIN for account access. It also ensures that withdrawal amounts are in multiples of 100 and checks for sufficient funds.

4. **User Information Display:** After each transaction, the system displays relevant user information, including account details, remaining balance, and, for teenagers, additional information based on their age and gender.

### Usage

1. **New User Setup:**
   - If a user is new, they provide their details, and the system generates a new account with a unique account number and PIN.

2. **Existing User Access:**
   - Existing users can access their accounts by providing their account number and PIN.

3. **Transaction Options:**
   - Users can choose from various transaction options, each providing a different banking functionality.

4. **Security Measures:**
   - The system ensures PIN validation and checks for sufficient funds for withdrawals.

### How to Run

1. Clone the repository to your local machine.
   ```
   git clone https://github.com/NeerajPrajapatiSDE/atm-project.git
   ```

2. Compile the program using a C++ compiler.
   ```
   g++ main.cpp atm.cpp -o atm
   ```

3. Run the executable.
   ```
   ./atm
   ```

### Notes

- This project serves as a basic template for an ATM system and can be extended for more complex features and improvements.

Feel free to explore and contribute to enhance the functionality and user experience of this ATM system!
