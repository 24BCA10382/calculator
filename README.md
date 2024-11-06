

---

### **Aim**  
To demonstrate and understand the functionality of the `switch-case` statement in programming, and to explore how it can be used as an alternative to multiple `if-else` conditions.

---

### **Objective**  
- To show how the `switch-case` construct can be used for decision-making based on a specific value.
- To compare the efficiency and readability of `switch-case` with multiple `if-else` conditions.
- To understand how `switch-case` can handle multiple cases, including default cases.

---

### **Procedure**  
1. **Set up the environment**:
   - Open a text editor or an Integrated Development Environment (IDE) where you can write and run code (e.g., Visual Studio Code, IntelliJ IDEA, etc.).

2. **Write the program**:
   - Declare a variable to hold an integer or character that you will use for the switch condition.
   - Implement the `switch-case` construct, where you will check the value of the variable against different possible cases.
   - In each case, output a specific result based on the value of the variable.
   - Implement a `default` case that will execute if no match is found.

   Example in C:

   ```c
   #include <stdio.h>

   int main() {
       int choice;
       printf("Enter a number between 1 and 5: ");
       scanf("%d", &choice);

       switch(choice) {
           case 1:
               printf("You chose option 1\n");
               break;
           case 2:
               printf("You chose option 2\n");
               break;
           case 3:
               printf("You chose option 3\n");
               break;
           case 4:
               printf("You chose option 4\n");
               break;
           case 5:
               printf("You chose option 5\n");
               break;
           default:
               printf("Invalid choice!\n");
       }

       return 0;
   }
   ```

3. **Execute the program**:
   - Run the program and input different values to test each case.
   - Observe how the program switches to the appropriate output based on the user's input.

4. **Analyze results**:
   - Check if the output matches the expected results for each case.
   - Test the behavior when an invalid value is entered (e.g., outside the range of 1 to 5).

---

### **Conclusion**  
- The `switch-case` statement is an efficient way to handle multiple conditional checks based on a single value.
- It can make the code more readable and maintainable compared to using multiple `if-else` statements, especially when there are many possible cases.
- The `default` case ensures that the program can handle unexpected or invalid inputs.
- `Switch-case` is particularly useful when you need to choose from a set of predefined options, like menus or user input validation.

