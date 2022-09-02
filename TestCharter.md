## **Exploratory Testing Session of the Monefy app**

|  Charter|  Analyse the Strawberry Menu options |
|--|--|
| **Tester**	 |Parvathi   
| **Priority**|Medium  |
|**Duration**|5-10 mins|

**Areas :**  
1. select accounts

2. cash payments

3. card payments

4. Timeline of Payments





 **Test Notes**
 

1.Tap on strawberry menu

- verify all accounts dropdown 

- verify day, week,month, year,all,interval,date selection and how it is displayed in homepage based on selection
- verify both past and future dates

|Bugs| None observed |
|--|--|
| **Test Result**	 |Pass
| **Issues**|None  |
|**Risks**|None|

----------------------------------------------------------------------------------------------------------------------------------

|  Charter|  Analyse the Home Page options |
|--|--|
| **Tester**	 |Parvathi   
| **Priority**|High|
|**Duration**| 35 mins|

**Areas :**  
 - Header logo and icons
 - Date and categories
 - Expense and Income options
 - Balance

 **Test Notes**
 
 
1.Verify logo and icons

 - verify the position of logo

 - verify search icon, strawberry menu and kebab menu and  transfer icon functionality.

 - verify expense and balance features

 - add expense and balance and verify it is updated in the middle circle.

 - Verify types of expense icons, add expense with them

 - Verify Date/day/Week/interval selection feature

 - Based on selection from top left strawberry menu, home page should display balance/expense based on the date/month/week or interval selection.
 - Verify balance feature

 - Balance should be updated based on expense and selection of carry over checkbox in top right kebab menu

**Bugs:**
 1. **Title**: Once an expense amount is added it cannot be edited.
**Steps to Reproduce**:
	 - Go to homepage
	- Select any category icon. For eg:Entertainment
	- Add the expense amount
	- Tap on add Entertainment button
	- Tap on the Entertainment category

**Actual Result** : New expense amount can be added

**Expected Result**: No option displayed to edit the existing expense. So if a user makes a wrong entry, it cannot be changed.

**Issues**:
		 - What is the amount depicted in blue colour? No clear indication of what amount it is and user has to guess what it means	.
	
**Risks**:
	- The balance and expense calculations accuracy, lack of labels causing confusion.
	-	No way to edit income and expense once entered.
	-	UI is cluttered and not very user friendly

-------------------------------------------------------------------------------------------------------------------------------------------------------------

|  Charter|  Analyse the Kebab Menu options |
|--|--|
| **Tester**	 |Parvathi   
| **Priority**|High|
|**Duration**| 25 mins|

**Areas :**  
1. Categories
2. Accounts
3. Currencies
4. Settings

 **Test Notes**

 1. Tap on Categories
	- Verify Add categories (expense and income:Premium feature, couldn’t test)
	- Verify Delete categories and home page category icon update after deletion
2. Tap on accounts
	 - Verify Add new account and validate if updated in accounts section under left strawberry menu
	- Verify adding money amount to accounts and validate home page is updated with the amount
	- Verify transfer amount functionality and update in home page
3. Tap on currencies (Premium feature, couldn’t test)

4. Tap on settings
	- verify balance
	- verify general settings
	- verify synchronization
	- verify data backup

**Bugs:**
 1. **Title**: Back button navigation is incorrect.
**Steps to Reproduce**:
	 - Go to homepage
	- Select top right kebab menu
	- Select categories
	- Select an expense/income
	- Select back button on phone

**Actual Result** : The menu bar closes and displays home page

**Expected Result**: it should navigate back to options in kebab menu ie categories,accounts,settings.

2. **Title**: Data backup and restore shows as backed up and restored although it is a premium feature
**Steps to Reproduce**:
	 - Go to homepage
	- Select top right kebab menu
	- Select settings
	- Select create data backup
	- Navigates to file explorer to save the backup file.
	- Select restore from same menu
	- Prompts to select file location for restore

**Actual Result** :  When backup or restore is selected user is navigated to file explorer to select the file location. File is also created. Message is also displayed – “data is restored”. Then premium feature page is displayed

**Expected Result**: If it is a premium feature, user should not be allowed to select a file location for backup or restore. Also, file restored message should not be displayed.

3. **Title**: Although language selection is a premium feature, language is updated in some places
**Steps to Reproduce**:
	 - Go to homepage
	- Select top right kebab menu
	- Select settings
	- Select language as French
	- Go to home page

**Actual Result** :   The premium feature page is displayed but in home page top center, date is displayed in French.

**Expected Result**:  If it is a premium feature, user should not be allowed to select a language and it should not be updated anywhere in the app.

**Issues**:
		 -  No information on what does  future recurring records feature do and how it affects the accounts
	
**Risks**:
	- Malware on the mobile device can cause personal financial data leakage, can read backup files from device
	-	Poor encryption and authentication; user can just open the app and start using it. No authentication is required. Backup files are also not encrypted










