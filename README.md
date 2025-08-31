# My First Excel Project

This is a project to document my journey of learning Excel from scratch.

### Lesson 1: The Spreadsheet Basics

I've learned that a spreadsheet is made up of a grid of **rows** (labeled with numbers) and **columns** (labeled with letters).
The intersection of a row and a column is called a **cell**, and each cell has a unique **cell address**, like A1 or C5.

---

### Lesson 2: Entering Data

I've learned that to enter data into a cell, you must first **select** it. The data you type will appear both in the selected cell and in the **Formula Bar** at the top of the spreadsheet. If a cell is empty, the Formula Bar will be blank.

---

### Lesson 3: Editing Data

I learned there are a couple of ways to edit data in a cell:

1.  You can select a cell and just start typing. This will replace the entire content of the cell.
2.  You can **double-click** the cell or click on the **Formula Bar**. This allows you to edit the existing content without having to re-type it all, which is very useful for making small changes.

---
### Lesson 4: Basic Calculations

I learned that the **equals sign (`=`)** is the key to telling Excel you want to perform a calculation. When you type a formula like `=2+2` and press Enter, the cell shows the **result** (`4`), while the **Formula Bar** shows the actual **formula**.

The real power of Excel is using **cell addresses** in formulas. When I typed `=A1+B1` to add the numbers from two different cells, the result automatically updated whenever the numbers in `A1` or `B1` changed.

---
### Lesson 5: Using Ranges and Functions

I learned that a **range** is a group of cells, like `A1:A5`. Using ranges makes it much easier to perform calculations on a large amount of data.

I also learned that Excel has built-in **functions** to perform common tasks, like:
* `=SUM()` to add up numbers in a range.
* `=AVERAGE()` to find the average.
* `=MAX()` to find the highest value.
* `=MIN()` to find the lowest value.

---
### Lesson 6: Formatting Data

I learned how to use Excel's built-in formatting tools to change how a number looks without changing its value. For example, by clicking the dollar sign symbol, I can format a number like `150` to display as `$150.00`. This is a quick way to make my spreadsheets easier to read and understand.

---
### Lesson 7: Shortcuts

I learned a powerful shortcut for copying formulas. Instead of dragging the fill handle, I can **double-click** it, and Excel will automatically copy the formula down to the last row where my data ends.

---
### Lesson 8: Absolute Referencing

I learned that **relative referencing** (like `A1`) automatically adjusts when you copy a formula. However, sometimes you want a cell to stay "locked" in place. To do this, I can use **absolute referencing** with the dollar sign (`$`), like `$B$1`, which prevents the cell reference from changing when the formula is copied.

---
### Lesson 9: Mixed Referencing

I learned that **mixed referencing** is used when you want to lock either the column or the row, but not both. For example, in a multiplication table, I used `=$A2*B$1` to make sure the formula always referred back to the correct column and row headers, no matter where I copied it.

---
### Lesson 10: Creating Charts

I learned how to create a visual representation of my data using charts. By selecting a range and going to the "Insert" tab, I can choose from different chart types, like a bar chart. I can also customize the chart's title and axis titles to make it easier to read.
