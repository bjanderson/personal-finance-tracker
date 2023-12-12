# Personal Finance Tracker

_Disclaimer: I am not a financial advisor, and this document/spreadsheet is not financial advice. For help with planning your finances please consult a professional financial advisor._

---

The secret to having good personal financial health is to simply keep track of where your money is, where it comes from, and where it goes to.
This is a spreadsheet document designed to help you do just that.

This document contains macros that help you set up spreadsheets for each of your accounts.
The macros are mostly just focused on stamping out the templates and setting up the formulas.
Once you understand how everything works, you can easily modify everything however you want to.

Let's get you started with your own copy of the document.

## Installation

### Install LibreOffice

First you will need to install LibreOffice, if you don't already have it.

Go to https://www.libreoffice.org/download/, and download the latest version of LibreOffice for your device.
They have [helpful documentation](https://www.libreoffice.org/get-help/install-howto/) if you need help figuring out how to get LibreOffice installed.

### Download The Document

Next you will need to download a copy of the document.

But before you download it I recommend creating a folder where you will keep the document from now on. Coming up, we will set up permissions for LibreOffice to run macros in this folder, so create a folder that will be dedicated to holding this document.

To get a copy of the document go to the project on my Github page at https://github.com/bjanderson/personal-finance-tracker/.

You can either download all the files in the project by clicking on the Code button and selecting Download ZIP, or you can click on the [personal-finance-tracker.ods](https://github.com/bjanderson/personal-finance-tracker/raw/master/personal-finance-tracker.ods) file and select any of the View raw, Raw, or Download buttons. This will prompt you to save the file and you can save it in the folder you created in the previous step.

### Enable Macros

Now go ahead and open the document.

When you open it for the first time you will get a warning that the document contains macros, and it will tell you where you can find the settings to change the macro security settings.

Take note of where the warning pointed you to, click OK, and go to that menu.

I run Linux, so I will click Tools > Options > LibreOffice > Security > Macro Security.

On Mac you will need to click LibreOffice > Preferences > LibreOffice > Security > Macro Security.

If you need help finding this menu, check the [documentation](https://help.libreoffice.org/latest/en-US/text/shared/optionen/01030300.html?DbPAR=SHARED#bm_id2322153).

In the Macro Security dialog click on the Trusted Sources tab.

In the Trusted File Locations section click the Add button.

Choose the folder that you created at the beginning to hold this document, and click OK to close the dialog windows.

Now close the document and re-open it so the macro security settings take effect. When you open it this time you should not see the macro security warning. If you do see the warning, make sure you have this document saved in the same folder that you added to the Trusted File Locations.

## Overview

### Summary Page

The Summary page is where you can see all your financial details in one place. You should use the information from your summary to create a budget, and determine how close you are to achieving your goals.

If you need to make changes to your financial habits, the summary will show you where you need to make those changes.

#### Balance Sheet

The Balance Sheet tells you where your money is at. It contains a list of all your accounts, and your balance in each account. The Balance Sheet allows you to measure if you are reaching your financial goals or not.

The Balance Sheet tells you three important pieces of information: your total assets, your total liabilities, and your net worth.

Your assets are money you own.

Your liabilities are money you owe.

Your net worth is your total assets minus your total liabilities - or how much money you will have left after you pay off all your debts.

If you have a negative net worth, then you owe more money than you have.

If you have a positive net worth, then you have more money than you owe.

You want to have a positive net worth!

#### Income Statement

The Income Statement tells you where you money comes from, and where it goes to. It contains a list of categories for your income and expenses. The Income Statment is the tool to use for creating a budget and making sure that you stick to it.

The Income Statement also tells you three important pieces of information: your total income, your total expenses, and your net income.

Your total income is all the money you received.

Your total expenses is all the money you paid.

Your net income is the amount of income you have left over after paying all your expenses.

If you have a negative net income it means you are spending more than you are earning.

If you have a positive net income it means you are earning more than you are spending.

You want to have a positive net income!

### Controls Page

The controls page has buttons that allow you to run a few special macros.

#### Add Account

The Add Account button allows you to add a new account to your document. You simply give the account a unique name (don't have two accounts with the exact same name), and choose the type of account it is.

Each account type generates a different type of template.

The account types are specified as either Assets or Liabilities, and when you create a new account, it will automatically be added to the Summary Balance Sheet in the correct section.

##### Account Types

- Checking - Asset
- Credit Card - Liability
- Equity - Asset
- Investment - Asset
- Loan - Liability
- Mortgage - Both*
- Savings - Asset

* When you create a mortgage account, a corresponding equity account will be generated automatically. The mortgage account allows you to track your loan, and the equity account allows you to keep track of the value of the property. Both parts are added to the Summary Balance Sheet so that you have a full view of the property as both an asset and a liability.

#### Remove Account

The Remove Account button allows you to remove an account.

The account will automatically be removed from the Summary page as well.

#### Add Category

The Add Category button allows you to create a new Income Statement category.

Use this to customize your income statement to reflect your budget categories.

When you add a new category, the income statement for each account, and on the Summary page will be regenerated in order to include it.

##### Category Types

Category Types come in four different flavors.

- Income
- Expenses
- Transfer
- Ignore

Income and Expenses are self-explanitory.

Transfer is when you move money from one account to another, such as from your checking account to your savings account, or when you make a credit card payment. It's not actually an income or an expense, it's a transfer.

Ignore is a category I rarely use, but every once in a while you might recieve a large inheritance or make a large purchase that you don't want to skew your Income Statment numbers. You can either make a category for "Large Income" or "Large Expense" or just ignore them. It's up to you.

#### Remove Category

The Remove Category button allows you to remove an Income Statement category.

The category will automatically be removed from all account income statements, and the Summary page as well.

### Data Page

The Data Page is not meant to be used by you. It's an internal data storage area for the macros to use.

If you edit it, you might break something, so I would avoid touching it unless you know what you're doing.

### Plan Page

The Plan page is a rough draft of a personal financial plan.

I threw it together as an example of how you might set up your own financial plan.

It might not seem too relevant at first, but once you start tracking your finances and seeing your actual numbers, you will probably want to take more control over you financial life. The Plan page will help you set goals and keep yourself on track. Make it your own.

## How To Use The Personal Finance Tracker
