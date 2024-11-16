# simple_react
getting started with react
Option 1: Quick Setup (Not Recommended for Production)
you can simply include this include these links in your HTML head section
        <!-- React -->
        <script src="https://unpkg.com/react@17/umd/react.development.js" crossorigin></script>
        <!-- React DOM -->
        <script src="https://unpkg.com/react-dom@17/umd/react-dom.development.js" crossorigin></script>
        <!-- Babel -->
        <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>

       1: First  React Link loads the core React library, which provides the ability to create React components, manage state, and handle props.
       2: Second Link  provides the ReactDOM library, which is responsible for rendering React components into the DOM (Document Object Model).
       3: Third link loads Babel Standalone, a JavaScript transpiler that converts modern JavaScript (like ES6 and JSX) into plain JavaScript that all browsers can understand.
       
Option 2: Modern Setup with React Installation (Recommended)
  For scalable and production ready-projects. Install React and setup Modern Environment
  Step 1: Install Node.js and npm
    ( Install Node.js from Node.js https://nodejs.org,)
    Ensure it's installed by running
      (node -v)
      (npm -v)

  Step 2: Create a New React App
  (npx create-react-app my-app )
  
  Step 3: Start the Development Server
  ( cd my-app )
  (npm start)

  Your app will open in a browser at http://localhost:3000/.
  
  Continue........
