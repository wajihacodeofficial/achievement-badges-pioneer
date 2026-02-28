# Aura UI Framework

A modern, lightweight CSS-in-JS library designed for high-performance React applications.

## Features

- **Zero Runtime:** Styles are extracted at build time for maximum speed.
- - **Type Safe:** Built with TypeScript for a first-class developer experience.
  - - **Atomic CSS:** Generates minimal CSS to reduce bundle size.
    - - **Theming:** Easy-to-use theming system with support for dark mode.
     
      - ## Installation
     
      - ```bash
        npm install aura-ui
        ```

        ## Usage

        ```javascript
        import { styled } from 'aura-ui';

        const Button = styled('button', {
          background: 'blue',
          color: 'white',
          padding: '10px 20px',
          borderRadius: '4px',
        });

        function App() {
          return <Button>Click Me</Button>;
        }
        ```

        ## License

        MIT
        
