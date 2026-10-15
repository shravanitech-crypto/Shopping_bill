# Shopping Bill – GST First, Discount After

## Project Description
This project implements a shopping bill calculator using Python.
It calculates GST on different categories of products, adds the
GST-inclusive amounts, and applies a 20% discount to the final total.

## Features
- Electronics GST calculation at 18%
- Fashion GST calculation at 13%
- Food GST calculation at 7%
- Total bill calculation after GST
- 20% discount on the total bill
- Final payable amount calculation

## Functions
1. `calculateElectronicsGST(a, b)` – Calculates 18% GST.
2. `calculateFashionGST(c, d)` – Calculates 13% GST.
3. `calculateFoodGST(e)` – Calculates 7% GST.
4. `totalBill(a, b, c, d, e)` – Returns the total after GST.
5. `calculateDiscountedBill(a, b, c, d, e)` – Returns the final bill after discount.

## Sample Test Case

**Input amounts:**
- a = 100
- b = 100
- c = 100
- d = 100
- e = 100

**Expected Results:**

| Calculation | Amount |
|---|---:|
| Electronics after GST | 236.00 |
| Fashion after GST | 226.00 |
| Food after GST | 107.00 |
| Total after GST | 569.00 |
| 20% Discount | 113.80 |
| Final Payable Amount | 455.20 |

## Technologies Used
- Python 3

## How to Use
Import or call the required functions from `shopping_bill.py`
and pass the five item amounts as arguments.

The functions return the calculated amounts without using
input statements or print statements.

## Author
Shravani Sirsat
