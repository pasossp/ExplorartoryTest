 **Exploratory Testing Session of the Monefy app**

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







