# Electricity Bill Calculator

## 📌 About the Project
A Python program that calculates electricity bills for multiple consumers based on the number of units consumed and predefined tariff slabs.

## ✨ Features
- Accepts the number of consumers.
- Takes each consumer's name and electricity usage.
- Calculates the bill using slab-based rates.
- Displays the consumer's name, units consumed, and total bill amount.
- Supports multiple consumers in one execution.

## 🛠️ Technologies Used
- Python 3
- Functions
- `for` Loop
- Conditional Statements (`if`, `elif`, `else`)
- User Input and Type Conversion
- Arithmetic Operations

## ⚡ Electricity Tariff Slabs

| Units Consumed | Rate per Unit |
|---|---:|
| First 100 units | ₹1.50 |
| 101–200 units | ₹2.50 |
| 201–500 units | ₹4.00 |
| Above 500 units | ₹6.00 |

## 🚀 How to Run
1. Install Python 3.
2. Download or clone this repository.
3. Open the project folder in VS Code.
4. Run the command:

   ```bash
   python electricity_bill.py
   ```

## 💻 Sample Output

```text
Enter number of consumers: 1

Customer 1
Enter customer name: Ravi
Enter units consumed: 250

Customer Name: Ravi
Units: 250.0
Bill Amount: Rs. 600.0
```

## 💡 Future Improvements
- Validate the number of units entered.
- Add fixed charges and taxes.
- Save consumer bills to a file.
- Generate a summary of all consumer bills.

## 👩‍💻 Author
Beginner Python Developer
