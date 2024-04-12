# :books: React Hooks Apps

This repository contains a collection of mini apps that uses React Hooks. You can use them to speed up your development or learning purposes.

All of them are using React, Javascript, and Bootsrap to make sure your eyes doesn't hurt that much.

## :file_folder: Contents

The 'src' folder contains the following examples Apps:

1. \`useState\`: Two different Counter App: One with `useState` and the other with a custom hook called `useCounter`.
2. \`useEffect\`: MessageApp, SimpleForm and FormWithCustomHook (which uses `useForm` custom hook).
3. \`examples\`: The worst Pokemon App you'll ever find!
4. \`useRef\`: Using the `useRef` hook.
5. \`just ignore this sh1t\`
6. \`memos\`: Using React.memo and `useMemo` hook.
7. \`tarea-memo\`: Another example with memo and `useCallback`.
8. \`useReducer\`: Here we've used `useTodo` and `useForm` (our custom hooks) and introduce the concept of `Reducer`.
9. \`useContext\`: This app is about Context. You'll find that it contains a UserContext that you can use in your app.

## :wrench: How to Use

To use any of these Apps, simply make sure you've uncommented the corresponding import of the component you want to run in main.jsx:

Example: In the main.jsx
```
import { TodoApp } from './08-useReducer/TodoApp';
```

Then, you can use the component as follows:

```
  <BrowserRouter>
    {/* <MainApp /> */}
    {/* <CounterApp /> */}
    {/* <CounterWithCustomHook /> */}
    {/* <FormWithCustomHook /> */}
    {/* <FocusScreen /> */}
    {/* <CallbackHook /> */}
    <TodoApp/> {/* TodoApp will be rendered */}
  </BrowserRouter>
```

## :warning: Important

Remember to install node modules by running the following command:

```bash
npm install
```

## :bulb: Contributing

If you have an idea, an improvement or if you detect a bug, feel free to open an Issue or a Pull Request.
