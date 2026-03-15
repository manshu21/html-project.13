Even or Odd Number Checker (JavaScript)
This is a simple JavaScript project that checks whether a number entered by the user is **Even or Odd**.
The program uses a **prompt input box** to take a number from the user and then determines the result using an **if–else condition**.

Technologies Used
1.HTML
2.CSS
3.JavaScript

Project Structure
project-folder
│
├── index.html
├── style.css
├── script.js
└── image.png

_How It Works_
1.The program asks the user to enter a number using `prompt()`.
2.JavaScript checks the number using a condition.
3.If the number is divisible by **2**, it is **Even**.
4.Otherwise, it is **Odd**.
5.The result is displayed in the **browser console**.

_JavaScript Code_

let num = prompt("Enter Your Number Here");

if (num % 2 == 0) {
console.log("Number is Even", num);
} else {
console.log("Number is Odd", num);
}

_Explanation_

1. `prompt()` → Used to take input from the user.
2. `%` → Modulus operator that returns the remainder.
3. `num % 2 == 0` → Checks if the number is divisible by 2.
4. `console.log()` → Displays the result in the browser console.

_How to Run the Project_

1. Download or clone the project folder.
2. Open the `index.html` file in a browser.
3. Enter a number in the popup input box.
4. Open the **browser console** to see whether the number is **Even or Odd**.

_Example_

Input:

```
Enter Your Number Here: 8
```

Output:

```
Number is Even 8


```
