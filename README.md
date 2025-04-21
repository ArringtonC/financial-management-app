# Financial Management Application

A robust financial management app that allows users to track account balances, manage debts, set and monitor financial goals, and receive AI-driven planning suggestions.

## Project Overview

This application provides users with a comprehensive set of tools to manage their finances, including:

- **Account & Debt Tracking**: Real-time balance updates, deposits, withdrawals, and debt management
- **Goal Setting & Planning**: Create and track financial goals with automated plan generation
- **Visualizations**: Interactive charts for account trends, debt payoff progress, and goal achievements
- **AI Integration**: AI-driven plan checking and optimization suggestions

## Getting Started

### Prerequisites

- Node.js 16 or higher
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/financial-management-app.git
cd financial-management-app
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Start the development server:

```bash
npm start
# or
yarn start
```

4. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Project Structure

```
financial-management-app/
├── public/                  # Static files
├── src/                     # Source code
│   ├── components/          # UI components
│   ├── controllers/         # Controller layer
│   ├── domain-classes/      # Domain logic
│   ├── tests/               # Test files
│   ├── utils/               # Utility functions
│   ├── App.tsx              # Main app component
│   └── main.ts              # Entry point
├── package.json             # Dependencies and scripts
└── tsconfig.json            # TypeScript configuration
```

## Development Workflow

1. **Feature Branches**: Create a new branch for each feature or bug fix
2. **Testing**: Write tests for all new functionality
3. **Pull Requests**: Submit pull requests to the `dev` branch
4. **Code Review**: All PRs require review before merging
5. **Main Branch**: Protected branch for stable releases

## Testing

Run tests with:

```bash
npm test
# or
yarn test
```

## Excel Prototype

The application also includes an Excel prototype with the following sheets:

- Dashboard
- Account Management
- Debt Tracking
- Goal Management
- AI Suggestions

The Excel prototype can be used to validate core functionality before implementation.

## Project Plan and Tasks

### January – Excel Prototype & Workflow Validation
- [x] Flesh out each sheet with real columns and sample data
- [x] Verify core formulas (SUMs, IF logic, progress calculations)
- [x] Review and refine Excel model's logic and naming
- [x] Draft spec-sheets for each Excel tab
- [ ] Scaffold VBA/macros for navigation
- [ ] Generate stubs for helper functions

### February – UML Finalization & UI Wireframes
- [x] Lock down comprehensive UML diagram
- [x] Create high-fidelity wireframes for all five screens
- [x] Audit UML for consistency and completeness
- [x] Provide feedback on wireframes
- [x] Generate boilerplate component files for each screen
- [x] Scaffold prop definitions based on wireframes

### March – Project Scaffolding & Git Workflow
- [x] Initialize Git repo with main and protected dev branches
- [x] Create folder structure
- [x] Review project README and contributing guides
- [x] Verify TypeScript interface definitions
- [ ] Generate Jest test stubs for each interface
- [ ] Scaffold basic CI pipeline YAML

### April – Account & Debt Domain Logic
- [x] Implement Account class with all methods
- [x] Implement Debt class with all methods
- [x] Write manual sanity checks
- [x] Code-review implementations for edge-cases
- [x] Refine JSDoc/TSDoc comments
- [x] Generate comprehensive unit tests

### May – Account & Debt UI Components
- [x] Build React components for deposit/withdraw forms
- [x] Build React components for debt-update forms
- [ ] Hook components up to controllers layer
- [ ] Review component props and state handling
- [ ] Suggest UX text improvements
- [ ] Scaffold component unit tests
- [ ] Generate Storybook stories or demo pages

### June – Goal Domain Logic & Wireframes
- [ ] Implement Goal class and PlanGenerator methods
- [x] Finalize wireframes for goal creation & display screens
- [ ] Validate goal-setting logic and algorithms
- [ ] Refine wireframe annotations for edge cases
- [ ] Generate unit tests for goal logic
- [ ] Scaffold React hooks for GoalController

### July – Goal & Plan UI Integration
- [ ] Build goal-management UI
- [ ] Build plan-viewer screen
- [ ] Wire up live data binding to controllers
- [ ] Review end-to-end user flows
- [ ] Suggest improvements in layout and call-to-actions
- [ ] Generate component tests for goal forms
- [ ] Scaffold integration tests

### August – AI/PlanChecker & Results Logic
- [ ] Implement AI_PlanChecker and Results classes
- [ ] Wire up suggestion logic
- [ ] Refine AI prompts and suggestion flows
- [ ] Audit result messages for clarity
- [ ] Generate unit tests for checkPlan()
- [ ] Scaffold mock AI response objects

### September – AI-Driven UI & Data Visualization
- [x] Build Results & Suggestions UI screens
- [x] Integrate interactive charts with Recharts
- [ ] Connect chart components to data endpoints
- [ ] Review chart accessibility
- [ ] Suggest improvements to labels and tooltips
- [ ] Scaffold chart component tests
- [ ] Generate snapshot tests for Results screen

### October – CI/CD, Branch Merging & Excel Sync
- [ ] Finalize GitHub Actions workflows
- [ ] Build import/export endpoints for Excel sync
- [ ] Audit CI/CD configurations
- [ ] Review data-sync API design
- [ ] Scaffold tests for import/export endpoints
- [ ] Generate utility scripts for data transformation

### November – End-to-End Testing & Polish
- [ ] Execute full regression test suite
- [ ] Run UAT session with test users
- [ ] Help triage user feedback
- [ ] Refine UI copy and error messaging
- [ ] Generate tests for edge cases
- [ ] Scaffold bug-fix test cases

### December – Beta Launch & Documentation
- [ ] Package and deploy beta builds
- [ ] Finalize user guides and marketing materials
- [ ] Proofread user-facing documentation
- [ ] Write release notes and onboarding text
- [ ] Generate utility scripts
- [ ] Scaffold documentation examples

## License

This project is licensed under the MIT License - see the LICENSE file for details
