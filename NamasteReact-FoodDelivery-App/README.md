# Namaste React 🚀

This project serves as a comprehensive guide and implementation of essential React concepts, including Parcel setup, React hooks, routing, Redux Toolkit, and testing. The project also includes an example application, **Namaste Food**, showcasing a practical structure for a food delivery web application.

---

## Features

### Parcel Setup
- Dev Build and Local Server.
- Hot Module Replacement (HMR).
- Advanced File-Watching Algorithm (written in C++).
- Caching for faster builds.
- Image Optimization and Minification.
- Bundling and Compression.
- Consistent Hashing and Code Splitting.
- Differential Bundling for older browsers.
- Diagnostics and Error Handling.
- Tree Shaking to remove unused code.
- Separate Dev and Production Bundles.

### React Concepts
#### React Hooks
- **useState()**: Manage state variables effectively.
- **useEffect()**: Handle side effects.

#### Routing
- **Client-Side Routing**: Handle dynamic content within the app without refreshing the page.
- **Server-Side Routing**: Manage routing logic from the server.

---

## Application Structure: Namaste Food
The project includes a sample **Namaste Food** application with the following structure:

### Header:
- Logo.
- Navigation Items.

### Body:
- Search Bar.
- **RestaurantContainer**:
  - Contains multiple **RestaurantCard** components.
  - Each card includes:
    - Restaurant Image.
    - Name of the Restaurant.
    - Star Rating.
    - Cuisine Type.
    - Delivery Time.

### Footer:
- Copyright Information.
- Useful Links.
- Address and Contact Details.

---

## Export and Import in JavaScript

### Default Export/Import:
```javascript
export default Component;
import Component from "path";
```

### Named Export/Import:
```javascript
export const Component;
import { Component } from "path";
```

---

## State Management with Redux Toolkit
1. Install `@reduxjs/toolkit` and `react-redux`.
2. Build a store and connect it to the app.
3. Define slices (e.g., `cartSlice`).
4. Dispatch actions to update the state.
5. Use selectors to retrieve state data.

---

## Testing in React

### Types of Testing:
1. **Unit Testing**: Test individual components or functions.
2. **Integration Testing**: Test the interaction between components.
3. **End-to-End (e2e) Testing**: Test the full workflow of the app.

### Setting Up Testing:
1. Install React Testing Library, Jest, and Babel dependencies.
2. Configure Babel and Parcel for testing.
3. Initialize Jest with `npx jest --init`.
4. Install `jsdom` and `@babel/preset-react` for JSX support.
5. Add `@testing-library/jest-dom` for extended DOM assertions.

---

## Getting Started

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd namaste-react
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Development Server
Start the development server:
```bash
npm start
```

---

## Contributing
Contributions are welcome! Please feel free to raise issues, suggest improvements, or submit pull requests.
