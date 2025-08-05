# CODE STANDARD
Adapted from: https://www.geeksforgeeks.org/coding-standards-and-guidelines/

**1.	Limited use of globals:**

These rules tell about which types of data that can be declared global:
- Data interface variables (I/O)
- Constants

**2.	Standard headers comments for different modules:**

For better understanding and maintenance of the code, the header of different modules should follow some standard format and information. The header format must contain below things that is being used in various companies:
- Name of the module
- Brief description about what the module does
- I/O description
- Global variables accessed or modified by the module

**3.	Naming conventions for local variables, global variables, constants and functions:**

Meaningful, short and understandable variables and functions name help anyone to understand the reason of using it.
- Local variables should be named using camel case lettering starting with small letter, including unit (if not dimensionless) separated by underscore (e.g. carAcceleration_ms2). Global variables names should be formed using capital letters only (e.g. GLOBALDATA).
- The names of the function should be written in camel case starting with capital letters (e.g. IsFunction()).
- The name of the function must describe the reason of using the function clearly and briefly.
- It is better to avoid the use of digits in variable names (eg. polar1, polar2, etc).

**4.	Indentation:**

Proper indentation is very important to increase the readability of the code. For making the code readable, programmers should use White spaces properly. Some of the spacing conventions are given below:
- There must be a space after giving a comma between two function arguments.
- Each nested block should be properly indented and spaced.
- Proper Indentation should be there at the beginning and at the end of each block in the program.
- All braces should start from a new line and the code following the end of braces also start from a new line.

**5.	Error/exception handling conventions:**

All functions that encountering an error condition should either return a 0 or 1 for simplifying debugging. Errors should not stop execution.

**6.	Avoid using a coding style that is too difficult to understand:**

Code should be easily understandable. The complex code makes maintenance and debugging difficult and expensive. Do not use “GO TO”.

**7.	Avoid using an identifier for multiple purposes:**

Each variable should be given a descriptive and meaningful name indicating the reason behind using it. This is not possible if an identifier is used for multiple purposes and thus it can lead to confusion to the reader (e.g. “i”, “j”, “k”, “ii”, “kkk”, etc). Moreover, it leads to more difficulty during future enhancements.

**8.	Code should be well commented:**

The code should be properly commented for understanding easily. Comments regarding the statements increase the understandability of the code.

**9.	Length of functions should not be very large:**

Lengthy functions are very difficult to understand. That’s why functions should be small enough to carry out small work and lengthy functions should be broken into small ones for completing small tasks. Avoid multiple task functions.

**10.	Hard coded values should be avoided:**

Values wrote directly in the code should be reduced. Avoid same value being included multiples times (e.g. “*1.944” for each m/s to kt conversion). Aircraf-related values should be moved to dedicated databases.
