# AI-Prolog-Programming

```markdown
# 📚 Prolog Programs Collection

This repository contains a collection of beginner-to-intermediate level Prolog programs covering recursion, list processing, arithmetic operations, and logic. Perfect for learning core Prolog concepts like pattern matching, backtracking, and rule definitions.

---

## 🔧 How to Run

Ensure you have [SWI-Prolog](https://www.swi-prolog.org/) installed.

To run any program:
```bash
swipl
?- [filename].   % load the file
?- predicate.    % run the main predicate
```

---

## 🧮 Factorial
**File:** `factorial.pl`

Calculates the factorial of a number.
```prolog
?- factorial.
Enter a number: 5
Factorial of 5 is 120
```

---

## 🔢 Fibonacci
**File:** `fibonacci.pl`

Computes the Nth term in the Fibonacci sequence.
```prolog
?- generate_fib.
Enter the value of N: 6
The 6th term of Fibonacci series is: 5
```

---

## 🤝 GCD
**File:** `gcd.pl`

Calculates the Greatest Common Divisor of two integers.
```prolog
?- gcd.
Enter the first number: 20
Enter the second number: 15
The GCD of 20 and 15 is 5
```

---

## 🔼 Power
**File:** `power.pl`

Computes exponentiation (base^power).
```prolog
?- power.
Enter the base number: 2
Enter the exponent: 4
The result of 2 raised to the power of 4 is 16
```

---

## ✖️ Multiplication
**File:** `multi.pl`

Multiplies two numbers.
```prolog
?- multi.
Enter the first number: 4
Enter the second number: 5
The result of 4 multiplied by 5 is 20
```

---

## 🔍 Membership Check
**File:** `memb.pl`

Checks if an element exists in a list.
```prolog
?- memb.
Enter a list: [1,2,3]
Enter an element to check: 2
2 is a member of [1,2,3]
```

---

## ➕ List Concatenation
**File:** `conc.pl`

Concatenates two lists.
```prolog
?- conc.
Enter the first list: [1,2]
Enter the second list: [3,4]
The concatenated list is: [1,2,3,4]
```

---

## 🔁 Reverse List
**File:** `reverse_list.pl`

Reverses a list.
```prolog
?- reverse_list.
Enter a list: [a,b,c]
Original list: [a,b,c]
Reversed list: [c,b,a]
```

---

## 🔄 Palindrome Check
**File:** `palindrome.pl`

Checks if a list is a palindrome.
```prolog
?- palindrome.
Enter a list: [1,2,1]
The list is a palindrome.
```

---

## ➕ Sum of List Elements
**File:** `sumlist.pl`

Calculates the sum of all elements in a list.
```prolog
?- sumlist.
Enter a list: [1,2,3]
The sum of the list is: 6
```

---

## 🔢 Even & Odd Length Checker
**File:** `evenlength.pl`

Checks if a list has even or odd length.
```prolog
?- evenlength.
Enter a list: [1,2]
The list has even length.

?- oddlength.
Enter a list: [1,2,3]
The list has odd length.
```

---

## 🆎 Nth Element
**File:** `nth_element.pl`

Finds the Nth element in a list.
```prolog
?- nth_element.
Enter a list: [a,b,c]
Enter the position: 2
The element at position 2 is b
```

---

## 🆙 Maximum in a List
**File:** `max_list.pl`

Finds the maximum number in a list.
```prolog
?- max_list.
Enter a list: [10, 2, 30, 5]
The maximum number in the list is: 30
```

---

## ➕ Insert at Nth Position
**File:** `insert_nth.pl`

Inserts an element at the Nth position of a list.
```prolog
?- insert_nth.
Enter the item to insert: x
Enter the position: 2
Enter the list: [a,b,c]
The modified list is: [a,x,b,c]
```

---

## ➖ Delete Nth Element
**File:** `delete_nth.pl`

Deletes the element at the Nth position.
```prolog
?- delete_nth.
Enter the position to delete: 2
Enter the list: [a,b,c]
The modified list is: [a,c]
```

---

## 🔀 Merge Two Sorted Lists
**File:** `merge_lists.pl`

Merges two **sorted** lists into one sorted list.
```prolog
?- merge_lists.
Enter the first ordered list: [1,3,5]
Enter the second ordered list: [2,4,6]
The merged list is: [1,2,3,4,5,6]
```

---

## 🧠 Author

**Muhammed Irshad P P**  
Data Analyst at Enlearn Academy  
Preparing for MS in CS/Robotics abroad (Germany focus)  
