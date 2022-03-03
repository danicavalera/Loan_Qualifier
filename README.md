# Loan Qualifier

This python command-line interface application allows users to see qualifying loans from lenders. The application works by taking in a `daily_rate_sheet` of loan criteria from various lenders, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans.


---

## Technologies

This project leverages python 3.8 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs



---

## Installation Guide

Before running the application first install the following dependencies.
```python pip install fire pip install questionary```

This will allow user to import modules to call on functions:

![Imports](file:///Users/danica/Desktop/Starter_Code/loan_qualifier_app/data/images/imports.png)
---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts.

![Loan Qualifier Prompts](file:///Users/danica/Desktop/Starter_Code/loan_qualifier_app/data/images/loan_qualifier_prompts.png)

## Contributors

Brought to you by Danica Valera - [Linkedin](https://www.linkedin.com/in/danica-valera-188184215)

---

## License
MIT