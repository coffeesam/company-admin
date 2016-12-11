# Company admin

> Filling annual returns (through ACRA) and tax (through IRAS) for Singapore based small company.

## Important numbers

- Bank account
- Company ID / UEN

## Check company compliance

Check company compliance status on [BizFile](http://www.bizfile.gov.sg) anytime with company UEN.

## Definitions

1. **Small EPC**: EPC with annual revenue up to S$5 million or less for financial years
1. **ECI**: Estimated Chargeable Income
1. **ACRA** affairs:
	- AGM (Annual General Meeting)
	- AR (Annual Returns)
1. **IRAS** affairs:
	- Income Tax Return

---

## Yearly tasks

1. [31 Jan](https://github.com/sayanee/company-admin#internal) (internal) - Calculate Revenue, Expense and Gross profit / loss for the previous year
1. [15 Nov](https://github.com/sayanee/company-admin#iras) - File Form CS online with IRAS
1. [15 Nov](https://github.com/sayanee/company-admin#acra) - File AGM / Annual Filling with ACRA

---

## Internal

> 31 Jan: Calculate Revenue, Expense and Gross profit / loss for the previous year

1. Calculate **revenue** from Invoices in [Freshbooks](https://freshbooks.com): `Reports > Item Sales > Export to > CSV`
	![](img/revenue.png)

1. Create **expense** from email (PayPal, eBay, Amazon, etc), OCBC transactions in [Freshbooks](https://crayonio.freshbooks.com): `Reports > Accounting > Expense Report > Export to > CSV`
	![](img/expense.png)

1. Download the `*.pdf` and `*.csv` of income and expense in the `Income/{YEAR}` and `Expense/{YEAR}` folders in the Dropbox
1. Create a Google Spreadsheet and keep it in the Google Driver Folder on `YYYY Income & Expense`
1. Import the 2 `*.csv` files into 2 sheets **Income** and **Expense**
1. Calculate **profit** `revenue - expense` in the 3rd sheet

---

## IRAS

> 15 Nov: File Form CS online in IRAS

1. Go to <https://mytax.iras.gov.sg>
1. Fill in the UEN-LOCAL-CO
1. Click `What I need to do`
	![](img/p1.png)

1. Click `File Form CS`
	![](img/p2.png)

1. Part A - All conditions met
	![](img/p3.png)

1. Part B - Tax Adjustments
	![](img/p4.png)

1. Fill up the numbers
	- Net Profit/Loss before Tax as per Accounts (Total income less total expenses per the Profit & Loss Statement.)
	- Gross Profit/Loss
(Enter negative sign for Gross Loss, e.g. '-123456')
	- Expenses
	![](img/p5.png)

1. Declaration of filing
	![](img/p6.png)

---

## ACRA

> 15 Nov: File AGM / Annual Filling with ACRA

1. Go to [Bizfile](http://www.bizfile.gov.sg/)
1. Explore eServices > Local Company > Filing of Annual Return by Local Company > UEN is `201113398Z`

	![](img/step1.jpg)
1. Fill up **Company Details** and click `Submit`
	![](img/step2.png)

1. Fill up **Annual Return Details** and click `Submit`
	![](img/step3.png)
	![](img/step4.png)

1. Fill up **Declaration** and click `Submit`
	![](img/step5.png)
1. Preview and pay `SGD 60`
1. Print the Acknowledgement
	![](img/step6.png)
