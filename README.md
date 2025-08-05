# Deloitte Data & Analytics Virtual Experience

This repository contains the tasks completed as part of a **free Data & Analytics virtual experience offered by Deloitte**.

## Certificate Earned
As part of this course, I completed two hands-on tasks involving real-world datasets and tools like **Tabulae** and **Excel** to better understand how to visualize and analyze compensation data.

## Task 1: Tabulae Dashboard (JSON-based)

- Used **Tabulae** to create a dynamic dashboard from a provided `.json` file.
- Gained hands-on experience in uploading data, selecting visualization types, and configuring filters and metrics.
- Exported the dashboard configuration as a JSON file for version control and reuse.
>  _You can view the dashboard JSON in the `dashboard.json` file in this repo._

## Task 2: Excel Analysis – Employee Compensation Equality

We were given a dataset (`Equality Table.xlsx`) containing:

- `Factory`
- `Job Role`
- `Equality Score` (ranging from -100 to +100, where 0 is ideal)

### Objective:
Create a **new column** called `Equality Class` to categorize the `Equality Score` into:

| Equality Score        | Classification          |
|-----------------------|--------------------------|
| Between -10 and +10   | Fair                     |
| <-10 or >10           | Unfair                   |
| <-20 or >20           | Highly Discriminative    |

### Example Classification:
- 10 → Fair  
- -9 → Unfair  
- -30 → Highly Discriminative

### Outcome:
- Learned to use Excel formulas (e.g., `IF`, `ABS`) to perform conditional classification.
- Understood how to interpret data distributions in workforce compensation.

## Files in this Repository

| File Name               | Description                                        |
|-------------------------|----------------------------------------------------|
| `dashboard.json`        | Tabulae dashboard configuration                   |
| `Equality Table.xlsx`   | Excel dataset with added "Equality Class" column  |
| `README.md`             | This file                                         |

## Key Learnings

- Basics of data visualization using **Tabulae**
- Data classification and analysis using **Excel**
- GitHub project setup and documentation

## Certificate



Feel free to explore the project files and reach out if you have any suggestions!
