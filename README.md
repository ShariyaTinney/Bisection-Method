
📐 Bisection Method in C++

📌 Overview

This project is a simple implementation of the Bisection Method using C++.

The Bisection Method is a numerical technique used to find the roots of nonlinear equations. It works by repeatedly narrowing the interval between two points that contain a root, based on the Intermediate Value Theorem.

>Equation used in this implementation:
>f(x) = x³ - x - 11

This method ensures that the root lies within the interval and progressively converges to it with increasing accuracy.


🎯 Features
✅ Calculates the root of a nonlinear equation using the Bisection Method
✅ Validates that the initial interval [a, b] contains a root
✅ Iterates until the desired precision (`EPSILON`) is reached
✅ Displays the root and the number of iterations it took to find it
✅ Written in clean, readable C++ code with detailed comments



🛠 Requirements
To run this project, you'll need the following:
A C++ compiler such as "g++" or "clang++"
An IDE or text editor to work with C++ code (e.g., "VS Code", "CLion", "Code::Blocks", or any text editor of your choice)



🚀 How to Run
1.Clone the repository or download the source code:
   ✅git clone https://github.com/shariyatinney/bisection-method-cpp.git
   ✅cd bisection-method-cpp

2. Compile the C++ code:
   ✅g++ main.cpp -o bisection

3.Run the program:
   ✅./bisection
   


🧠 How It Works

✅The method begins by accepting two initial values, a and b, which represent the interval endpoints
✅2.It checks whether the function values at a and b have opposite signs (i.e., the root lies between "a" and "b").
✅The midpoint "c" is then calculated as:
               c = (a + b)\2
✅4.If the function at c (f(c)) is close enough to zero, or the interval width is smaller than the specified tolerance (EPSILON), the method stops and returns c as the root.
✅Otherwise, based on the sign of f(c), the interval is halved, and the process repeats until convergence.
✅This method guarantees that the root lies within the interval [a, b] and progressively narrows it until the root is approximated with the desired accuracy.


📁 File Structure
bisection-method-cpp/
├── main.cpp      # Main C++ program implementing the Bisection Method
└── README.md     # Project documentation (this file)



📤 Sample Output
✅After running the program with an initial interval [2, 3], the output will look like:
Bisection Method for f(x) = x^3 - x - 11
The root is: 2.58008
Number of iterations: 10



🔧 Customization
You can customize the following parameters:
✅ Modify the function f(x) inside the func() method to solve a different equation.
✅ Change the initial guesses a and b in the "main()" function to choose a new interval for the root.
✅ Adjust the error tolerance (EPSILON) to control the precision of the result.



🤝 Contributions
Contributions are welcome!
Feel free to:
* Fork the repository
* Create a new branch
* Submit a pull request with improvements
If you have any suggestions or encounter issues, please open an "Issue" on the GitHub repository.


📧 Contact
For any questions or feedback, feel free to contact:
"ShariyaTinney" — \[[shariyatinney.gmail@example.com](mailto:shariyatinney.gmail@example.com)]

>Reminder:
> ✅ Replace `YOUR_USERNAME` in the Git clone URL
> ✅ Replace `Your Name` and `your.email@example.com` with your actual name and email before publishing.


📚 Resources
[Bisection Method – Wikipedia](https://en.wikipedia.org/wiki/Bisection_method)
[Numerical Methods in C++](https://cplusplus.com/)



🧩 Language
![C++](https://img.shields.io/badge/C%2B%2B-100%25-blue)



💡 Future Improvements

* Optimize performance by adding a "max iteration count" to prevent infinite loops in extreme cases.
* Extend the program to support other root-finding algorithms, such as "Newton Raphson Method" or "Secant Method".
* Implement **user input** for initial guesses and tolerance.



