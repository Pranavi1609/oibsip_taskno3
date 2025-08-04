# 🏧 ATM Interface System

A comprehensive Java console application that simulates an ATM (Automated Teller Machine) interface with essential banking operations. This project demonstrates object-oriented programming principles, user authentication, and secure transaction handling in Java.

---

## 🌟 About This Project

This is **Task 3** from the **Oasis Infobyte Student Internship Program (OIBSIP)** - Java Development track. The ATM interface provides a realistic banking experience with secure login, balance management, and transaction history tracking.

---

## 💳 Features

- 🔐 **Secure Authentication**: PIN-based user verification system
- 💰 **Balance Inquiry**: Check current account balance
- 💸 **Cash Withdrawal**: Withdraw money with balance validation
- 💵 **Cash Deposit**: Add funds to your account
- 📊 **Transaction History**: View detailed transaction records
- 🔄 **Multiple Sessions**: Support for continuous operations
- ⚠️ **Error Handling**: Robust input validation and error management
- 🚪 **Safe Exit**: Secure logout functionality

---

## 🛠️ Technology Stack

- **Language**: Java 8+
- **Core Libraries**: java.util.Scanner, java.util.ArrayList, java.time.LocalDateTime
- **Programming Paradigm**: Object-Oriented Programming (OOP)
- **Development Environment**: Any Java IDE (Eclipse, IntelliJ IDEA, VS Code)
- **Runtime**: Java Virtual Machine (JVM)

---

## 📁 Project Structure

```
oibsip_taskno3/
├── ATMinterface.java          # Complete ATM system implementation
└── README.md                  # Project documentation
```

---

## 🚀 How to Run

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Any Java IDE or text editor
- Command line/terminal access

### Installation & Execution

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pranavi1609/oibsip_taskno3.git
   ```

2. **Navigate to project directory:**
   ```bash
   cd oibsip_taskno3
   ```

3. **Compile the Java file:**
   ```bash
   javac ATMinterface.java
   ```

4. **Run the ATM system:**
   ```bash
   java ATMinterface
   ```

---

## 💡 How to Use

### 1. **Login Process**
- Enter your account number
- Provide your 4-digit PIN
- System validates credentials

### 2. **Main Menu Options**
```
=== ATM INTERFACE ===
1. Check Balance
2. Withdraw Money
3. Deposit Money
4. View Transaction History
5. Exit
```

### 3. **Available Operations**

#### 💰 **Balance Inquiry**
- Displays current account balance
- Shows available funds for withdrawal

#### 💸 **Cash Withdrawal**
- Enter withdrawal amount
- System checks sufficient balance
- Updates balance and records transaction
- Dispenses cash (simulated)

#### 💵 **Cash Deposit**
- Enter deposit amount
- System adds funds to account
- Updates balance and records transaction
- Provides deposit confirmation

#### 📊 **Transaction History**
- Displays chronological list of all transactions
- Shows transaction type, amount, and timestamp
- Maintains running balance history

---

## 🔒 Security Features

- **PIN Authentication**: 4-digit PIN verification
- **Session Management**: Secure login/logout process
- **Input Validation**: Prevents invalid transactions
- **Balance Protection**: Prevents overdraft situations
- **Transaction Logging**: Maintains audit trail

---

## 💻 Technical Implementation

### Core Classes & Methods:
```java
// Main ATM Class
public class ATMinterface {
    // User authentication
    private boolean authenticateUser()
    
    // Balance operations
    private void checkBalance()
    private void withdrawMoney()
    private void depositMoney()
    
    // Transaction management
    private void showTransactionHistory()
    private void recordTransaction()
}
```

### Key Programming Concepts:
- **Encapsulation**: Private methods and data protection
- **Data Structures**: ArrayList for transaction storage
- **Exception Handling**: Try-catch blocks for error management
- **User Input Handling**: Scanner class for console interaction
- **Date/Time Operations**: LocalDateTime for timestamps

---

## 🎯 Sample Usage

```
Welcome to ATM Interface
========================

Enter Account Number: 123456789
Enter PIN: 1234

Login Successful!

=== ATM INTERFACE ===
1. Check Balance
2. Withdraw Money
3. Deposit Money
4. View Transaction History
5. Exit

Select Option: 1
Current Balance: $1,500.00

Select Option: 2
Enter withdrawal amount: $200
Transaction Successful!
Amount Withdrawn: $200.00
Current Balance: $1,300.00
```

---

## 🏆 Learning Outcomes

This project helps you master:

- ✅ **Object-Oriented Programming**: Classes, objects, and methods
- ✅ **Data Management**: Arrays and collections handling
- ✅ **User Interface Design**: Console-based menu systems
- ✅ **Input Validation**: Error handling and data validation
- ✅ **Security Concepts**: Authentication and authorization
- ✅ **Financial Logic**: Banking operations and calculations
- ✅ **Code Organization**: Modular programming structure

---

## 🚀 Future Enhancements

Advanced features for continued learning:

- [ ] **Multiple Account Support**: Handle different account types
- [ ] **Interest Calculation**: Savings account interest computation
- [ ] **Transfer Operations**: Money transfer between accounts
- [ ] **Receipt Generation**: Print transaction receipts
- [ ] **Account Creation**: New user registration system
- [ ] **Admin Panel**: Administrative functions and reporting
- [ ] **Database Integration**: Persistent data storage
- [ ] **GUI Interface**: Swing or JavaFX graphical interface
- [ ] **Mobile Banking**: SMS/Email notifications
- [ ] **Multi-language Support**: Localization features

---

## 📚 About OIBSIP

This project was completed as part of the **Oasis Infobyte Student Internship Program**:
- **Program**: Java Development Internship
- **Task**: Task 3 - ATM Interface System
- **Duration**: 4 weeks
- **Focus**: Advanced Java programming and system design

---

## 🔧 Troubleshooting

### Common Issues:

**Compilation Error:**
```bash
# Ensure Java is properly installed
java -version
javac -version
```

**Runtime Issues:**
- Verify all file paths are correct
- Check for proper input formatting
- Ensure sufficient system memory

**Input Problems:**
- Use numeric inputs for PIN and amounts
- Follow menu option numbers exactly
- Press Enter after each input

---

## 🤝 Contributing

Contributions are welcome! Areas for improvement:

1. **Security Enhancements**: Additional authentication methods
2. **Feature Additions**: New banking operations
3. **UI Improvements**: Better user experience design
4. **Code Optimization**: Performance improvements
5. **Documentation**: Enhanced code comments

### How to Contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

---

## 🙏 Acknowledgments

- **Oasis Infobyte** for the comprehensive internship program
- **Java Community** for excellent documentation and resources
- **Banking Industry** for inspiration on ATM functionality
- **Open Source Contributors** for best practices and guidance

---

 secure banking operations! Clone and run the ATM interface today! 🏧💳**
