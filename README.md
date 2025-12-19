# 📊 Financial Calculator – NPV & IRR

## 📌 Project Overview
This project is a Financial Calculator developed as Assignment 01.
It calculates two important investment evaluation metrics:

- Net Present Value (NPV)
- Internal Rate of Return (IRR)

Additionally, a comparison feature is implemented to determine which of two
investment projects is better based on NPV and IRR values.

## 🎯 Objective
To build a Python-based financial calculator that:
- Computes NPV for a series of cash flows at a given discount rate
- Computes IRR using an iterative numerical method
- Compares two investment projects and recommends the better option

## 📘 Financial Concepts Used

### 🔹 Net Present Value (NPV)
NPV represents the total present value of future cash flows discounted back
to today.

Decision Rule:
- NPV > 0 → Project is profitable
- NPV < 0 → Project should be rejected

### 🔹 Internal Rate of Return (IRR)
IRR is the discount rate at which the NPV becomes zero.

Decision Rule:
- IRR > Discount Rate → Project is acceptable
- IRR < Discount Rate → Project should be rejected

## 📊 Example Used

Year | Cash Flow
---- | ----------
0 | -1000
1 | 300
2 | 300
3 | 300
4 | 300
5 | 300

Discount Rate: 8%

Results:
- NPV = 197.81
- IRR = 15.24%

Since NPV > 0 and IRR > 8%, the project is acceptable.

## ✨ Unique Feature (Creative Twist)
This project includes a comparison feature:
- Two investment projects are evaluated
- The calculator compares NPV and IRR values
- The better project is recommended automatically

## 🧮 Implementation Details

### Technologies Used
- Python
- Jupyter Notebook

### Functions Implemented
- npv(cashflows, rate)
- irr(cashflows)

## ▶️ How to Run the Project

1. Clone the repository:
   git clone <repository-link>

2. Open Jupyter Notebook:
   jupyter notebook

3. Run all cells to view the results

## 🏁 Conclusion
The calculator successfully computes both NPV and IRR and compares two
investment projects. This helps in making better investment decisions.

## 👤 Author
Name: Minhal Siddiqui  
Assignment: 01
