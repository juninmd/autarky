```markdown
# AGENTS.md Guidelines

These guidelines outline the principles and requirements for the development of AGENTS.md, a repository for AI coding agents.  Adherence to these principles is crucial for maintaining a clean, maintainable, and reliable codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent module should have a single, well-defined purpose.  Avoid creating redundant code for similar functionality.
*   **Abstraction:**  Abstract complex logic into reusable components.  Don't expose implementation details unless absolutely necessary for a specific test case.
*   **Code Reuse:**  Utilize existing libraries and design patterns whenever appropriate.  Favor well-documented and tested code over custom solutions.
*   **Consistent Naming Conventions:**  Employ consistent naming conventions throughout the codebase for modules, functions, and variables.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimize Complexity:**  Strive for straightforward and easily understandable code. Avoid over-engineering solutions.
*   **Readability:** Prioritize code clarity and maintainability. Use meaningful variable names and comments judiciously.
*   **Small Functions:** Keep functions concise and focused on a single task.  Aim for functions that fit within a reasonable size (ideally under 50 lines).

## 3. SOLID Principles

*   **Single Responsibility Principle (Repeat):**  Each class/module should have one reason to change.
*   **Open/Closed Principle:**  The system should be extensible without modifying its core implementation.  New functionality should be added as separate, independent components.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to marshal and unmarshal data into interfaces they don't use.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Only implement functionality that is currently required.  Don't introduce features that are not essential for the current project's goals.
*   **Focus on Requirements:**  Prioritize implementation based on clearly defined requirements.  Don't add features simply because they "might be useful later."

## 5. Development Practices

*   **Unit Testing:**  All modules must be thoroughly unit tested.
*   **Code Reviews:**  All code changes should undergo a mandatory code review process before being merged.
*   **Documentation:**  Provide clear and concise documentation for each module and function, including inputs, outputs, and any assumptions.
*   **Error Handling:**  Implement robust error handling to gracefully handle unexpected situations.
*   **Logging:**  Use logging to track program execution and identify potential issues.

## 6. Testing

*   **Comprehensive Test Suite:**  The codebase must support a comprehensive set of automated tests, including unit tests, integration tests, and potentially end-to-end tests.
*   **Test Coverage:** Aim for 80% test coverage across all modules.  Automated testing will be used to drive this goal.
*   **Test Design:** Tests must be designed to cover various scenarios and edge cases.

## 7. File Size Limit (180 Lines)

*   All files within the AGENTS.md repository must not exceed 180 lines of code.

## 8.  Code Standards

*   Follow the established coding style guide (details in separate document, but it emphasizes readability and consistency).
*   Use consistent indentation and whitespace.
*   Employ meaningful variable and function names.

## 9.  AGENTS.md Structure (Example)

*   **Modules:**  Organize code into logical modules (e.g., `AgentsCore`, `DataProcessing`, `Communication`).
*   **Classes:**  Define classes for agents and related functionality.
*   **Data Structures:**  Clearly define data structures and their usage.
*   **Configuration:**  Provide a clear mechanism for configuring agents and their behavior.

## 10.  Commit Strategy

*   Commit frequently with small, logical changes.
*   Document each commit with a clear explanation of the changes.
*   Use clear commit messages.
```