# ⚠️ EXP-16: Exception Handling in C++

## 🎯 Aim

To understand and implement **exception handling** in C++ by:  
1. Handling divide-by-zero errors.  
2. Handling invalid age input (age below 18 for voting eligibility).  

---

## 📚 Theory

- **Exception Handling**  
  Exception handling in C++ provides a way to react to runtime errors (exceptions) in a controlled manner.  
  It uses **try**, **catch**, and **throw** keywords:  

  - **try** → Block of code where exception may occur.  
  - **throw** → Used to signal the occurrence of an exception.  
  - **catch** → Handles the exception thrown.  

- **Common Exceptions Covered in this Experiment:**  
  1. **Divide by Zero Error** → Division operation with denominator = 0.  
  2. **Invalid Age for Voting** → Age less than 18 is not valid for voting.  

---

## 🧮 Algorithms / Steps

### a) **Divide by Zero Exception**
1. Take two numbers as input (numerator & denominator).  
2. Inside a `try` block, check if denominator == 0.  
3. If true, `throw` an exception.  
4. Catch the exception using a `catch` block and display an error message.  
5. Otherwise, perform division and display the result.  

### b) **Age Validation for Voting**
1. Take age as input.  
2. Inside a `try` block, check if age < 18.  
3. If true, `throw` an exception.  
4. Catch the exception and display `"Not eligible for voting"`.  
5. Otherwise, display `"Eligible for voting"`.  

---

## ✅ Conclusion

- Exception handling allows programs to run **safely without crashing** when runtime errors occur.  
- Divide-by-zero exceptions show how arithmetic errors can be controlled.  
- Age validation demonstrates exception handling for **logical errors**.  
- Overall, exception handling improves **program reliability and robustness**.  

---

## 🧵 Topics Covered

- Exception Handling in C++  
- try, catch, throw mechanism  
- Divide by Zero Handling  
- Age Validation for Voting Eligibility  
- Safe and Robust Error Handling  
