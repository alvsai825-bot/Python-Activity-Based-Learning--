# Python Activity-Based Learning

**Subject:** Python Programming
**Activity:** Select any 10 case studies from the given list and develop
complete Python solutions

**Name:** AKKALA LAKSHMI VENKATA SAI
**Roll No:** 26000414

---

## Case studies selected

| # | Case study (number in the given list) | Folder |
|---|---------------------------------------|--------|
| 1 | Hospital Billing and Patient Classification (3) | [01-hospital-billing-patient-classification](01-hospital-billing-patient-classification/) |
| 2 | Railway Fare and Reservation Calculator (6) | [02-railway-fare-reservation-calculator](02-railway-fare-reservation-calculator/) |
| 3 | ATM Transaction Sequence Simulation (13) | [03-atm-transaction-sequence-simulation](03-atm-transaction-sequence-simulation/) |
| 4 | Smart Parking Fee Management (15) | [04-smart-parking-fee-management](04-smart-parking-fee-management/) |
| 5 | Objective Examination Answer String Evaluation (31) | [05-exam-answer-string-evaluation](05-exam-answer-string-evaluation/) |
| 6 | Nested Loop Calendar Generator (37) | [06-nested-loop-calendar-generator](06-nested-loop-calendar-generator/) |
| 7 | Multi-Branch Sales Matrix Comparison (43) | [07-multi-branch-sales-matrix-comparison](07-multi-branch-sales-matrix-comparison/) |
| 8 | Tuple-Based Product Catalogue Audit (49) | [08-tuple-product-catalogue-audit](08-tuple-product-catalogue-audit/) |
| 9 | Smart Canteen Order and Stock Management (57) | [09-smart-canteen-order-stock-management](09-smart-canteen-order-stock-management/) |
| 10 | Comprehensive Smart Campus Management Simulation (100) | [10-smart-campus-management-simulation](10-smart-campus-management-simulation/) |

## What is submitted in each folder

Every case study folder has all the deliverables asked for in the activity:

- `README.md` — problem statement, objectives, assumptions, algorithm,
  flowchart, pseudocode, source code, test cases, output and conclusion
- `flowchart.png` — flowchart of the program
- `solution.py` — the Python program
- `test_cases.py` — the test cases written to check the program
- `output.txt` — full text output of the program
- `output_screenshot.png` — screenshot of the output
  (case 9 and case 10 have a second screenshot because their output is long)
- `demo_input.txt` — the scripted input used for the menu-driven program
  (case 10 only)

## Topics used from the syllabus

| Topic | Where it is used |
|-------|------------------|
| Variables, data types, operators | all 10 |
| Conditional statements | all 10 |
| Loops | all 10 |
| Strings and string operations | 4 (HH:MM validation), 5 (answer sheets), 8 (code format) |
| Pattern generation | 5 (grade bars), 6 (calendar box), 10 (banners, resource bars) |
| Lists | 1, 3, 5, 9, 10 |
| Nested lists | 6 (calendar grid), 7 (sales matrix), 9 (menu), 10 (marks matrix) |
| Tuples and tuple operations | 2 (fare slabs), 8 (catalogue audit), 10 (student records) |
| Tuple unpacking | 1, 2, 4, 8, 9, 10 |
| Computational thinking, algorithm, flowchart, pseudocode | documented in every folder's README |

## How to run

```bash
# run any solution
python3 01-hospital-billing-patient-classification/solution.py

# the menu-driven program, with the recorded input
python3 10-smart-campus-management-simulation/solution.py < 10-smart-campus-management-simulation/demo_input.txt

# run the test cases of any case study
python3 01-hospital-billing-patient-classification/test_cases.py
```

Every test file prints a line per test and a pass/fail count at the end.

## Test summary

| Case study | Tests | Result |
|------------|-------|--------|
| 01 Hospital Billing | 21 | all passing |
| 02 Railway Fare | 23 | all passing |
| 03 ATM Simulation | 21 | all passing |
| 04 Smart Parking | 25 | all passing |
| 05 Answer Sheet Evaluation | 25 | all passing |
| 06 Calendar Generator | 23 | all passing |
| 07 Sales Matrix Comparison | 22 | all passing |
| 08 Catalogue Audit | 30 | all passing |
| 09 Smart Canteen | 30 | all passing |
| 10 Smart Campus Simulation | 38 | all passing |
| **Total** | **258** | **all passing** |

## Notes

- Only Python 3 is needed. No external packages are imported anywhere — the
  programs use only the syllabus topics listed above.
- The sample data used in every program is hypothetical. It was chosen so that
  each rule written in the problem statement actually fires somewhere in the
  output, including the rejection and boundary cases.
- I have run all ten test files and all 258 test cases pass.
- Submission: this repository, `Python-Activity-Based-Learning`.
