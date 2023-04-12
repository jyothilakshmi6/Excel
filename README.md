1. Add a new column titled "Surcharge" next to the "Discount" column.
2. In the first row of the Surcharge column, enter the formula:
=IF(E2="Same Day",0.2,IF(E2="First Class",0.1,IF(E2="Standard Class",0.05,0)))
3. This formula checks the Ship Mode in the corresponding row (in this case, E2) and assigns the appropriate surcharge value based on the conditions mentioned in the assignment. If none of the conditions are met, it returns a value of 0.
4. Drag the formula in step 3 down to apply it to all rows in the Surcharge column.
5. Add a new column titled "Total Cost" next to the "Profit" column.
6. In the first row of the Total Cost column, enter the formula:
=(S2-V2)*(1+W2)
7. Here, S2 is the Sales value in the corresponding row, V2 is the Profit value, and W2 is the Surcharge value.
8. Drag the formula in step 6 down to apply it to all rows in the Total Cost column.
9. That's it! Now the Excel sheet should have two new columns - Surcharge and Total Cost - which were calculated based on the conditions given in the assignment.
10. Google sheet for this can be accessed here.
https://docs.google.com/spreadsheets/d/1PCK2idSU1nvK-1dlmmndSk9GlH_BfmKc/edit#gid=611882830
