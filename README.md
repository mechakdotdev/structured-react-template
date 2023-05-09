# structured-react-template
A React template for proper folder structure with React JS and TypeScript intended to follow best practises.


Example
```
src/
├── components/
│   ├── common/
│   │   ├── Button/
│   │   │   ├── Button.tsx
│   │   │   └── Button.scss
│   │   ├── Input/
│   │   │   ├── Input.tsx
│   │   │   └── Input.scss
│   │   └── ...
│   ├── pages/
│   │   ├── HomePage/
│   │   │   ├── HomePage.tsx
│   │   │   └── HomePage.scss
│   │   ├── AboutPage/
│   │   │   ├── AboutPage.tsx
│   │   │   └── AboutPage.scss
│   │   └── ...
│   └── ...
├── services/
│   ├── api.ts
│   └── ...
├── store/
│   ├── actions/
│   ├── reducers/
│   ├── types/
│   ├── configureStore.ts
│   └── index.ts
├── styles/
│   ├── _variables.scss
│   ├── _mixins.scss
│   └── ...
├── utils/
│   ├── helpers.ts
│   └── ...
├── App.tsx
├── index.tsx
└── ...
```

- components/: Contains all of the reusable and standalone components used in the application, organized by their nature. For example, common/ contains common components used throughout the application, while pages/ contains components used for specific pages.
- services/: Contains files that interact with external services or APIs, such as an API client or socket service.
- store/: Contains all of the Redux-related files, including actions, reducers, and types, as well as the store configuration file.
- styles/: Contains the global styles, such as variables, mixins, and global stylesheets.
- utils/: Contains helper functions or classes used throughout the application.
- App.tsx: The root component of the application that defines the layout and routes of the application.
- index.tsx: The entry point of the application that renders the App component.

Some additional best practises to follow:
- Use PascalCase for component names and camelCase for variable and function names.
- Define prop types using TypeScript interfaces.
- Use functional components instead of class components where possible.
- Keep the components small and focused on a single responsibility.
- Use CSS modules or CSS-in-JS for component styles to avoid naming collisions and improve maintainability.
- Use Redux or another state management library for complex state management.
- Use async/await instead of Promises or callbacks for async operations.
- Use linters and formatters to ensure consistent code style and formatting.
- Use Git and a version control system to keep track of changes and collaborate with others.
