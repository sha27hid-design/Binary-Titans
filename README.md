# PennyWise — Smart Personal Finance Manager

## 1. Project Description

**PennyWise** is a personal finance management web application designed to help users understand, organize, and manage their spending. It aims to make expense tracking easier by presenting financial information in a simple, accessible interface.

The project focuses on helping users monitor expenses, understand spending patterns, and make more informed financial decisions. It was developed as a software project using modern web development tools, with AI-assisted development used where appropriate.

### Problem Statement

Many people struggle to keep track of their daily expenses, identify unnecessary spending, and maintain a budget. Manually recording transactions and analyzing spending patterns can be time-consuming.

PennyWise aims to simplify this process through a centralized interface for managing personal financial information.

### Objectives

- Simplify expense tracking and financial organization.
- Present financial information in an understandable format.
- Help users identify spending patterns.
- Provide a user-friendly and responsive interface.
- Use AI development tools responsibly to improve productivity while retaining human understanding and control over the code.

## 2. Key Features

> Update this list to match the features actually implemented in your version.

- **Expense Management:** Record and organize personal expenses.
- **Dashboard:** Present an overview of financial information.
- **Spending Analysis:** Help users understand where their money goes.
- **Budget Management:** Support budgeting and expense monitoring, if implemented.
- **Responsive Interface:** Make the application accessible across supported screen sizes.
- **AI-Assisted Development:** Use AI tools for brainstorming, code assistance, debugging suggestions, and UI improvements.

## 3. Technology Stack

Replace or remove technologies that your project does not use.

| Component | Technology |
|---|---|
| Frontend | React |
| Development Server | Vite |
| Programming Language | JavaScript / TypeScript |
| Styling | CSS / Tailwind CSS |
| Backend | [Actual backend technology] |
| Database | [Actual database, if used] |
| AI Integration | [Actual AI API/model, if integrated] |
| Development Tools | VS Code, browser developer tools, Git |

**Important:** Using AI to help write code is different from integrating an AI model into the application. Document an AI API as an application technology only if PennyWise actually calls it.

## 4. AI Tools Used

Fill in the tools your team actually used during development.

| AI tool | Purpose |
|---|---|
| [ChatGPT / other assistant] | Understanding requirements, brainstorming features, generating code suggestions, and troubleshooting |
| [GitHub Copilot / other coding assistant] | Code completion and development assistance, if used |
| [Other tool] | [Specific purpose] |

AI tools were used as development assistants rather than unquestioned sources of code. Suggested implementations were reviewed, tested, and modified where necessary to fit the project's requirements.

## 5. Important Prompts Used

The following are representative prompts suitable for documenting an AI-assisted workflow. Retain only prompts that reflect what your team actually asked.

### Prompt 1: Project Planning

> Help me plan a personal finance management web application called PennyWise. Identify the core user problems, essential features, and a realistic minimum viable product. Prioritize features that can be implemented and tested within a limited development timeframe.

**Purpose:** Establish the project's scope and prioritize essential functionality.

### Prompt 2: User Interface Development

> Help me create a clean and responsive dashboard for a personal finance application called PennyWise. Organize the interface so users can quickly understand their expenses and financial summaries. Keep the components modular and use the existing project's technology stack.

**Purpose:** Explore UI structure, component design, and layout improvements.

### Prompt 3: Code Generation and Explanation

> Help me implement [specific component or feature] in PennyWise. Explain the logic, describe the purpose of each important function, and ensure that the implementation is compatible with the existing codebase. Avoid changing unrelated files.

**Purpose:** Generate an initial implementation while maintaining an understanding of the code.

### Prompt 4: Debugging Assistance

> Analyze the following code and the observed error. Identify the likely root cause, explain why it occurs, and suggest the smallest safe fix. Consider edge cases and explain how I can verify that the fix works.

**Purpose:** Obtain debugging guidance and possible solutions without blindly replacing existing code.

### Prompt 5: Code Improvement

> Review this implementation for readability, maintainability, and edge cases. Suggest improvements without changing its intended behavior. Explain each proposed change and identify any tests needed to confirm that it still works.

**Purpose:** Improve code quality and evaluate AI-generated suggestions.

## 6. AI-Generated Code That Was Modified

AI-generated code was treated as a starting point rather than automatically accepted as the final implementation.

Document at least one real example below.

**Feature or file:** [Name of the component, function, or file]

**Initial AI-generated implementation:**  
[Briefly describe what the AI initially generated.]

**Changes made by the team:**
- [Describe a specific change to the generated logic or component.]
- [Explain why the original implementation was unsuitable.]
- [Describe any corrections for compatibility, styling, validation, or edge cases.]

**Reason for modification:**  
The initial suggestion did not fully match [the project's requirements, existing component structure, expected behavior, or another verified reason]. The team reviewed the code and modified it to meet the actual requirements.

**Verification:**  
[Describe how the modified implementation was tested and what the result was.]

This section should identify an actual modification, not merely a change to variable names or formatting unless that was genuinely the only modification made.

## 7. Bug Solved Independently by the Team

This section documents a bug that a team member diagnosed and fixed independently, without relying on AI to provide the actual solution.

**Bug title:** [Short, descriptive title]

**Problem observed:**  
[Describe what happened, including the relevant user action or input and the unexpected result.]

**Root cause:**  
[Explain the underlying technical reason discovered by the team.]

**Independent debugging process:**

1. Reproduced the issue using the relevant application workflow.
2. Inspected the affected component, function, browser console, network request, or application state.
3. Traced the behavior to the underlying cause.
4. Implemented a targeted fix based on the diagnosis.
5. Repeated the test to verify that the issue was resolved.

**Solution implemented:**  
[Describe the actual code or logic change.]

**Result:**  
The fix was verified by [describe the successful test]. The application subsequently behaved as expected for the tested scenario.

> Replace every bracketed field with your real bug and solution. If AI helped diagnose or fix this particular issue, choose a different bug that your team genuinely solved independently.

## 8. Testing and Validation

The team should document the tests actually performed, such as:

- Checking that the main pages load correctly.
- Testing input fields and form validation.
- Verifying that financial values and calculations are correct.
- Checking that user interactions produce the expected results.
- Testing error cases and missing or invalid inputs.
- Confirming that recent code changes do not break existing functionality.
- Checking the interface at different screen sizes, if responsive design is supported.

Only mark tests as completed when they have been run.

## 9. Challenges and Learnings

During development, the team had the opportunity to explore software design, component integration, debugging, and the use of AI-assisted programming tools.

Key learning outcomes include:

- Breaking a larger application into manageable features.
- Understanding and adapting generated code rather than accepting it without review.
- Diagnosing software defects through systematic testing.
- Integrating components into an existing project structure.
- Recognizing the importance of validating AI-generated suggestions.
- Collaborating to deliver a working application within the available timeframe.

## 10. Running the Project Locally

The following instructions assume a Vite-based frontend. Adjust them to match the actual project configuration.

### Prerequisites

- Node.js and npm
- Git, if cloning the repository
- Any required backend or database services

### Installation

```bash
git clone <your-repository-url>
cd <your-project-folder>
npm install
npm run dev
```

Open the local development URL displayed in the terminal. For the current development setup, this may be `http://localhost:5173/`.

If the project uses a backend, configure its environment variables and start the required services according to the project's setup instructions.

### Environment Variables

Store API keys and other secrets in local environment files that are excluded from version control. Provide a sanitized `.env.example` file where appropriate.

Never commit real API keys, passwords, or private financial information.

## 11. Conclusion

PennyWise demonstrates the application of software development practices to a practical personal finance problem. The project emphasizes usability, maintainable implementation, testing, and responsible AI-assisted development.

By combining human decision-making with AI-supported planning and coding, the team aims to build a useful application while developing its own programming, debugging, and problem-solving skills.

---

## Project Information

- **Project Name:** PennyWise
- **Project Type:** Web Application
- **Development Stage:** [Prototype / MVP / Completed]
- **Team Members:** Shahid S and Vikram Govindarajan
- **Repository:** [Add repository URL]
- **Demo:** http://localhost:5173/
