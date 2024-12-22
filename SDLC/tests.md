## Testing

![image](tests.png)

These tests are done during the 'Testing' phase of the Software Development Life Cycle (SDLC).

## Unit Tests

* **Why they are important:** Unit tests provide a foundation by ensuring individual code units work correctly.
* **Focus:** Individual units of code (e.g., functions, methods, classes).
* **Goal:** Verify that each unit behaves as expected in isolation.
* **Scope:** Smallest testable parts of the code.
* **Examples:**
    * Testing if a specific function returns the correct output for given inputs.
    * Checking if a class correctly initializes its properties.
    * Verifying that error handling within a method works as designed.

## Integration Tests

*   **Why they are important:** Integration tests build upon the foundation, by verifying that units work together seamlessly within the system.
* **Focus:** Interactions between different parts of the system.
* **Goal:** Ensure that components work together as intended.
* **Scope:** Larger than unit tests, involving multiple units or modules.
* **Examples:**
    * Testing data flow between different modules.
    * Verifying that a database interaction works correctly within the system.
    * Checking the integration of a user interface with backend services.

## User Interface (UI) Tests

*   **Why they are important:** UI tests ensure that the user interface functions correctly and responds well.
*   **Focus:** The user interface elements and their interactions.
*   **Goal:** Verify that the UI behaves as expected and that users can interact with it effectively.
*   **Scope:** Specific UI elements, or entire screens.
*   **Examples:**
    * Testing if buttons, menus, and forms work as expected.
    * Verifying the UI layout and responsiveness across different screen sizes.
    * Testing the flow of navigation through the app.

## User Acceptance Tests (UAT)

*   **Why they are important:** User acceptance tests are the final step, ensuring that the system meets the needs and expectations of the users.
* **Focus:** End-user perspective and satisfaction.
* **Goal:** Determine if the software meets the needs and expectations of the users.
* **Scope:** The entire system or specific features.
* **Examples:**
    * Real users testing the software in a realistic environment.
    * Business stakeholders verifying that the software meets their requirements.
    * Checking if the user interface is intuitive and easy to use.

## Key Differences Summarized

| Feature | Unit Tests | Integration Tests | UI Tests | User Acceptance Tests |
|---|---|---|---|---|
| **Focus** | Individual units | Interactions between components | User interface elements | End-user perspective |
| **Scope** | Smallest testable parts | Multiple units or modules | UI elements or screens | Entire system or features |
| **Goal** | Verify individual unit behavior | Ensure components work together | Verify UI behavior and responsiveness | Meet user needs and expectations |
| **Performed by** | Developers, often automated | Developers or testers, often automated | Developers or testers, often automated | End-users or stakeholders |

**In essence:**

* Unit tests provide a foundation by ensuring individual code units work correctly.
* Integration tests build upon that by verifying that these units work together seamlessly within the system.
* UI tests help to ensure the user interface is functional and responsive.
* User acceptance tests are the final step, ensuring that the system meets the needs and expectations of the end-users.
