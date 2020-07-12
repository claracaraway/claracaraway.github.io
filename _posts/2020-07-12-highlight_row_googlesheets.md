---
layout: single
title: "How to Highlight Entire Row in Google Sheets if Single Cell Contains X"
tags: dailylog
classes: wide
---

PROBLEM: I have a whole document filled with dates and I want to highlight all the Mondays

SOLUTION:

[REFERENCE](https://www.benlcollins.com/spreadsheets/conditional-formatting-entire-row/)

1. Format > Conditional Formatting
2. Apply to Range (I selected whole sheet)
3. Custom Formula Is rule
4. `=$A2=Monday`

ALSO: Here is how to add a `WEEKNUM` column

`=WEEKNUM(your-date-column)`
