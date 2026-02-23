# Study of For Loop in Python

---

## * Name - Yashasavi Jain
## * PRN - 25070123127
## * Batch - B3

---

# * Aim
To Study For Loop in Python and understand its working through different examples like number printing, sum of N numbers, matrix operations, patterns and combinations.

---

# * Theory

The for loop in Python is used to repeat a block of code multiple times.  
It is mainly used when we know how many times we want to repeat the statement.

A for loop works with sequences like:
* List  
* Tuple  
* String  
* Range  

### Syntax of For Loop

```python
for variable in sequence:
    statement(s)
```

The loop runs until all items in the sequence are completed.

---
# * Algorithm

---

## 1️⃣ Print Numbers from 1 to 5

* Start  
* Initialize loop variable `i`  
* Use `range(1,6)` to generate numbers from 1 to 5  
* For each value of `i`, execute the loop  
* Print the value of `i`  
* Repeat until the loop ends  
* Stop  

---

## 2️⃣ Sum of First N Numbers

* Start  
* Declare variable `n`  
* Take input from the user and store in `n`  
* Initialize variable `total = 0`  
* Use loop from 1 to `n` (using `range(1, n+1)`)  
* Add each value of `i` to `total`  
* Repeat until loop completes  
* Display the final value of `total`  
* Stop  

---

## 3️⃣ 3×3 Matrix Display

* Start  
* Initialize a 3×3 matrix with values  
* Use outer loop for rows (0 to 2)  
* Use inner loop for columns (0 to 2)  
* Access each element using `a[i][j]`  
* Print each element with space  
* After each row, move to next line  
* Repeat until all rows are printed  
* Stop  

---

## 4️⃣ Multiplication of Two 3×3 Matrices

* Start  
* Initialize first matrix `a`  
* Initialize second matrix `b`  
* Create result matrix with all elements as 0  
* Use outer loop for rows of matrix `a`  
* Use second loop for columns of matrix `b`  
* Initialize sum for each position  
* Use third loop to multiply corresponding elements  
* Add multiplication result to `result[i][j]`  
* Repeat until all rows and columns are completed  
* Display the final result matrix  
* Stop  

---

## 5️⃣ Print All Possible Combinations of Three Digits

* Start  
* Initialize three digits  
* Store digits inside a list  
* Use first loop for first digit position  
* Use second loop for second digit position  
* Use third loop for third digit position  
* Check condition that digits are not repeated  
* If condition is true, print the combination  
* Repeat until all possibilities are checked  
* Stop  

---

## 6️⃣ Right Angle Triangle Pattern

* Start  
* Set the starting value from 5 to 1  
* Use loop in reverse order (`range(5,0,-1)`)  
* For each iteration, print stars equal to value of `i`  
* Move to next line after each row  
* Repeat until loop ends  
* Stop  

---

## 7️⃣ Pyramid Pattern

* Start  
* Initialize number of rows (5)  
* Use loop from 1 to number of rows  
* Print spaces equal to `(rows - i)`  
* Print stars equal to `i`  
* Move to next line  
* Repeat until pyramid is complete  
* Stop  

---
---

# * Conclusion

In this experiment, we studied the for loop in Python.

We learned:
* Printing numbers using loop  
* Calculating sum of N numbers  
* Using nested loops  
* Matrix display and multiplication  
* Pattern printing  
* Generating combinations  

The for loop is very useful for repeating tasks and working with sequences in Python.

---
