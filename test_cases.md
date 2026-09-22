## Test Cases for Software Engineering Design Models

### Test Case 1: Usecase Diagram Verification (Positive Test)
*   **Description:** Verify if the usecase diagram correctly reflects the system boundaries and actor interactions.
*   **Input Data:** Check diagram for "User" actor linked to "Login" and "View Dashboard" use cases.
*   **Expected Output:** All primary actors are successfully mapped to their corresponding system actions with correct relationship arrows.
*   **Status:** Pass

### Test Case 2: UML Class Diagram Relationships (Negative/Validation Test)
*   **Description:** Ensure there are no isolated or disconnected classes within the structure.
*   **Input Data:** Validate relationship lines (inheritance, association) between classes like "User", "Admin", and "Database".
*   **Expected Output:** Every class connects logically to the main system architecture; zero orphan classes are found.
*   **Status:** Pass

### Test Case 3: SRS Requirement Traceability (Boundary Test)
*   **Description:** Check if the design models completely cover the basic functional requirements in the SRS document.
*   **Input Data:** Cross-reference functional requirement FR-01 (User Authentication) with the Usecase diagram.
*   **Expected Output:** The diagram explicitly covers the authentication flow as dictated by the requirements.
*   **Status:** Pass
*
