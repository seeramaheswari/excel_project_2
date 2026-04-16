# excel_project_2
## Transforming data range into table
### Removing duplicate values
### Questions /Insights

**Checking  total amount with customerid using vlookup**
>=VLOOKUP(D4,Table14[#All],9,0)

**Check for total amount by category wise**
>check for total amount by category wise

**Checking quantity of orders monthwise**
>=SUMIF(Table1[Month_Name],D11,Table1[Quantity])

**Checking mode of payment using  index and match**
>=INDEX(Table14[PaymentMode],MATCH(Question!D13,Table14[OrderID],0))

**Checking Total amount orders of each month**
>=SUMIF(Table1[Month_Name],D16,Table1[TotalAmount])

**Checking category wie quantity of customers ordered**
>=COUNTIF(Table14[Category],D19)
**Checking full details of an customer using filter function**
>=FILTER(Table14,Table14[OrderID]=C21)


