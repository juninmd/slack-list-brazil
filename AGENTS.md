```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality code for our AI coding agents. Adherence to these principles will promote a productive development workflow.

**1. DRY (Don't Repeat Yourself)**

*   **Core Logic:** All core logic, algorithms, and data structures should be encapsulated in reusable functions and classes.
*   **Component Modules:**  Break down complex functionalities into smaller, cohesive components.  Each component should have a single, well-defined purpose.
*   **Avoid Redundant Code:**  Refactor code to eliminate duplication across different modules.
*   **Single Responsibility Principle:** Each function/class should have one, and only one, reason to change.

**2. KISS (Keep It Simple, Stupid)**

*   **Simplicity is Key:** Favor straightforward, easy-to-understand code over complex or convoluted solutions.
*   **Minimize Complexity:**  Avoid unnecessary abstractions or conditional statements.
*   **Readability:** Prioritize clear and consistent formatting and naming conventions.
*   **Explainable Code:**  Write code with comments explaining *why* rather than *what* it does.  Inline explanations are acceptable where clarity is crucial.

**3. SOLID Principles**

*   **Single Responsibility Principle (SRP):** A class should have only one reason to change.
*   **Open/Closed Principle:** A class should be open for extension but closed for modification.  (This is less directly applicable here, but consider it if modifying existing functionality later.)
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on abstractions they do not use.
*   **Dependency Inversion Principle (DIP):** High-level modules should be replaced by low-level modules that provide the necessary dependencies.

**4. YAGNI (You Aren't Gonna Need It)**

*   **Avoid Unnecessary Features:**  Don't implement functionalities just because they *might* be useful in the future.
*   **Future-Proofing:** Design systems with the understanding that requirements may change.
*   **Focus on Current Tasks:**  Prioritize completing the essential elements of a given task, rather than building unnecessary features.

**5. Code Length & Structure**

*   **Maximum Code Length:**  Each file shall not exceed 180 lines of code.
*   **Modularization:**  Code should be organized into logical blocks with well-defined sections.
*   **Naming Conventions:**  Follow consistent naming conventions (e.g., camelCase for functions and variables, snake_case for classes).  Use a standard style guide (provided separately).
*   **Comments:**  Provide clear and concise comments where necessary to explain complex logic or non-obvious code.  Focus comments on *why*, not *what*.

**6. Testing & Mocking**

*   **Unit Tests:** All code must be thoroughly tested through unit tests.
*   **Mocking:** Mocking will *only* be used for tests. No real dependencies or state will be employed.
*   **Test Coverage:** Aim for at least 80% test coverage. Automated test suite must be developed and maintained.
*   **Test Driven Development (TDD):**  Implement tests before implementing the code.

**7. Code Style & Formatting**

*   **Indentation:**  Use consistent indentation (2 spaces).
*   **Line Length:**  Maintain a maximum line length of 120 characters.
*   **Whitespace:**  Use whitespace consistently to improve readability.
*   **Naming:**  Use meaningful names for variables, functions, and classes.

**8.  Specific File Format Considerations:**

*   Each file should have a unique filename, following a consistent naming convention.
*   File contents should be easily parsable by a standard parser (e.g., JSON, YAML).
*   File headers should include a brief description of the file's purpose.

**9.  Documentation**

*   Provide a `README.md` file within each file, explaining its purpose, dependencies, and usage.
*   Consider adding a `documentation.md` file detailing the overall architecture.

These guidelines are intended as a starting point.  We will revisit and refine them as the project evolves.  Any changes will be documented thoroughly.
```