# Mini Corporate Employee Database
Console-based basic employee data management program. Fully built on Java.

<em>Built by [@dashadriano](https://https://github.com/dashadriano)</em>

# Access
Clone this repository using:

```bash
git clone https://github.com/dashadriano/console-employee-database
```

Move into cloned repository's new directory, then run following command to complie:

```bash
javac consoleEmployeeDatabase.java
```

After compiling, run the program using:

```bash
java consoleEmployeeDatabase
```

At start-up, the program asks for administrator credentials, editable within the source code but on default is set to: 

username: `admin`<br>
password: `1234`

To clarify, this is a security liability. For more serious use cases, it is advised to implement concepts that would aid in obscuring sensitive data such as administrator credentials. The program developed is not suitable as an actual employee database. The creation of this mini project was solely to test the understanding of the developer.

# Development
The program only utilizes a single Java file. 

The file runs via a single class that contains multiple functions, code blocks compartmentalized according their respective utilities, that work through loops regulated by logical response to user inputs via conditional statements.

The main app instance is labeled as `app`, running within the `main` method of the program after passing login authentication as long as the program is not terminated via user choice. For a more in-depth look, view `basicPayrollSystem.java` to observe the logic flow used to regulate loops and execute code necessary to run the program.
