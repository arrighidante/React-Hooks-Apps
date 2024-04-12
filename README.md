# :books: React Hooks Apps

This repository contains a collection of mini apps that uses React Hooks. You can use them to speed up your development or learning purposes.

## :file_folder: Contents

The repository contains the following examples Apps:

1. \`useState\`: Two different Counter App: One with useState and the other with a custom hook called useCounter.
2. \`useEffect\`: MessageApp, SimpleForm and FormWithCustomHook (which uses useForm custom hook).


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

## :bulb: Contributing

If you have an idea, an improvement or if you detect a bug, feel free to open an Issue or a Pull Request.
