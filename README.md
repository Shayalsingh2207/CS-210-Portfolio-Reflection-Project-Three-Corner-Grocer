CS 210 Portfolio Reflection – Project Three: Corner Grocer
Project Summary

The Corner Grocer project was designed to solve a practical business problem: tracking and analyzing the frequency of grocery items purchased throughout the day. The program reads a text file containing a list of items sold, counts the frequency of each item, and allows users to interact with a menu to view individual item counts, print all item frequencies, and display a histogram for easy visualization. The program also saves the results to a backup file for data persistence.

What I Did Well

I did a great job organizing my program using object-oriented principles by creating a GroceryItem class to encapsulate item data and behavior. My code follows a clean, modular structure with meaningful variable names and detailed inline comments, making it easy to read and maintain. I also ensured robust input validation in the user menu to handle unexpected entries gracefully.

Where I Could Enhance the Code

I could enhance my code by implementing file error handling and data validation more extensively—for example, checking for missing input files or corrupted data before processing. I could also use a data structure like std::unordered_map for faster lookups if performance became a concern. These improvements would make the program more efficient and secure, especially when scaling to larger datasets.

Challenges and How I Overcame Them

The most challenging part of this project was correctly parsing and normalizing text input from the file, especially when dealing with mixed cases and punctuation. To overcome this, I used functions from the <algorithm> and <cctype> libraries to clean and convert strings consistently. I also reviewed documentation and coding forums to better understand C++ string manipulation.

Transferable Skills

From this project, I strengthened my skills in C++ file I/O, data encapsulation, vector iteration, and algorithmic problem solving. These skills will be highly transferable to future projects, especially in data processing and software design. I also gained valuable experience working in Visual Studio and using GitHub for version control, which are essential tools in professional software development.

Code Maintainability and Readability

I made this program maintainable and adaptable by using clear function separation, consistent indentation, and descriptive naming conventions. Each section of code is documented with comments explaining its purpose. The structure allows future developers to easily modify or extend the functionality—for example, to add new reports or data analysis features without rewriting major portions of the program.
