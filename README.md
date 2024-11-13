## Code Laws

1. Component names will be in PascalCase.
2. All new components will be functional components.
3. Component lines should not exceed 350 lines unless unavoidable.
4. Use Redux only to save backend information that needs to be used app-wide.
5. Use a flat component structure for designing flows (child component level should not exceed 2, unless unavoidable).
6. Use Context API if the flow is large and requires managing many components with many states.
7. Only use `let`, `const`, and arrow functions.
8. Avoid using array native functions, prefer Lodash instead.
9. Design components should be made common inside the modules folder.
10. Avoid JSX variables unless unavoidable.
11. Declare states at the top, unless unavoidable.
12. Library imports should be on top, followed by a space, and then the rest of the imports.
13. For TypeScript Props definitions, required props come first, followed by a space, and then optional props.
14. No inline styles unless necessary, and try to clean them up if present.
15. No inline function definitions.
16. All functions and variables will use underscores (`_`).
17. App Flows: Organize screens that work together cohesively.
18. File and folder structure:
   - **Feature Name Folder**
   - **Feature Name File**
   - **Logic separation**: Feature File contains all the logic.
   - **Components Folder**: For child components.
   - **Styles**: Separated from logic.
   - **Helpers**: Utility functions.
   - Write styles and logic inside the component if the file doesn't exceed 350 lines.
   - **Data Transformers**: To handle data transformations.
   - **Context**: Stored in `context.ts`.
19. String localization: Add text lines in the `en` file and use the `t` function to translate.
20. Squash and merge feature/fix branches.
21. Branch naming:
    - `feat-{feature-name}`
    - `fix-{fix-name}`
    - `chore-{chore-name}`

22. Generic Library Rules:  
    Follow generic library rules. Use Text and other design patterns consistently.
