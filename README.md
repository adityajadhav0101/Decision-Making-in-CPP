**💻 Decision Making**

**🎯 Aim**

To explore key decision-making structures in C++—including if-else, if-else-if ladder, and switch-case—through foundational examples like checking odd/even, finding the largest of three numbers, identifying vowels or consonants, and using switch statements.

**📚 Theory**

🔹 Conditional statements control the flow of execution based on evaluated conditions, allowing for dynamic and flexible logic handling.
🔹 These constructs are crucial for enabling programs to “think” and respond to input or state variations.

**🔄 If-Else Statement**

The _if-else_ structure allows a program to make a binary decision. If a condition evaluates as true, one block of code is executed; otherwise, the alternate block runs. It’s useful for simple, yes/no logic checks where you’re choosing between two distinct paths.

**🧭 If-Else-If-Else Ladder**

This expands decision-making to multiple conditions. The program evaluates conditions sequentially from top to bottom. As soon as one condition is true, its corresponding block runs, and the rest are skipped. The final _else_ acts as a fallback if none of the prior conditions match. Ideal for layered logic where multiple outcomes are possible.

**🎚️ Switch-Case Statement**

The _switch-case_ structure offers a cleaner alternative to multiple _if_ checks when you're dealing with discrete values (like menu options or fixed states). It matches the value of a variable against predefined cases and executes the matched case block. A _default_ case handles anything that doesn’t fit the listed options.

**Algorithm: Odd or Even Number Detection**

1️⃣ Start<br>
2️⃣ Declare an integer variable _num_<br>
3️⃣ Prompt the user to enter a number<br>
4️⃣ Input the number into _num_<br>
5️⃣ Check if _num % 2 == 0_<br>
&nbsp; &nbsp; &nbsp;✔️ If true → Display "Even"<br>
&nbsp; &nbsp; &nbsp;❌ Else → Display "Odd"<br>
6️⃣ End<br>

**Algorithm: Largest of Three Numbers**

1️⃣ Start<br>
2️⃣ Declare three integer variables _a_, _b_, and _c_<br>
3️⃣ Prompt the user to enter all three numbers<br>
4️⃣ Input the values<br>
5️⃣ Compare:<br>
&nbsp; &nbsp; &nbsp;✔️ If _a > b && a > c_ → Display _a_ is largest<br>
&nbsp; &nbsp; &nbsp;✔️ Else if _b > c_ → Display _b_ is largest<br>
&nbsp; &nbsp; &nbsp;❌ Else → Display _c_ is largest<br>
6️⃣ End<br>

**Algorithm: Vowel or Consonant Using ASCII**

1️⃣ Start<br>
2️⃣ Declare a character variable _ch_<br>
3️⃣ Prompt the user to enter a character<br>
4️⃣ Input _ch_<br>
5️⃣ Check if _ch_ is between _'A'-'Z'_ or _'a'-'z'_ (ASCII 65–90 or 97–122)<br>
&nbsp; &nbsp; &nbsp;✔️ If true → Check if _ch_ is _'A', 'E', 'I', 'O', 'U'_ or lowercase equivalents<br>
&nbsp; &nbsp; &nbsp;✔️ If true → Display "Vowel"<br>
&nbsp; &nbsp; &nbsp;❌ Else → Display "Consonant"<br>
&nbsp; &nbsp; &nbsp;❌ Else → Display "Not a letter"<br>
6️⃣ End<br>

**Algorithm: Month Selector Using switch-case**

1️⃣ Start<br>
2️⃣ Declare an integer variable _choice_<br>
3️⃣ Display menu options for months (1–12)<br>
4️⃣ Prompt the user to enter a choice<br>
5️⃣ Input _choice_<br>
6️⃣ Use _switch(choice)_<br>
&nbsp; &nbsp; &nbsp;✔️ Match cases from 1–12 to corresponding month<br>
&nbsp; &nbsp; &nbsp;❌ If no match → Display "Invalid Input"<br>
7️⃣ End<br>

**🧠 Conclusion**

Decision-making is at the heart of intelligent programming. Whether you're branching logic with if-else, scaling conditions with else-if ladders, or simplifying options via switch-case, mastering these structures equips you to write smarter, more dynamic code. Let the compiler follow your logic line by line, decision by decision.🚀
