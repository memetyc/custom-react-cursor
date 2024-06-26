# Custom React Cursors

Custom React Cursors is a library that allows you to create custom cursor effects in your React applications.

## Installation

You can add Custom React Cursors to your project using npm or yarn.

```bash
npm install custom-react-cursors
```
or
```bash
yarn add custom-react-cursors
```

### Usage
To use Custom React Cursors, import the CustomCursor component into your project and include it in your component tree.

```bash
import React from 'react';
import CustomCursor from 'custom-react-cursors';

function App() {
  return (
    <>
      <CustomCursor ringColor={'hotpink'} ballColor={'hotpink'} />
      {/* Your other components */}
    </>
  );
}

export default App;
```
In the above example, the CustomCursor component is imported from the custom-react-cursors package and included in the App component. You can customize the appearance of the cursor by passing ringColor and ballColor props to the CustomCursor component.

### Customization
The CustomCursor component supports the following props for customization:

  ringColor: Specifies the color of the ring around the cursor.
  ballColor: Specifies the color of the cursor ball.

For example, to customize the cursor with a hot pink ring and ball, you can use:

```
<CustomCursor ringColor={'hotpink'} ballColor={'hotpink'} />
```
<<<<<<< HEAD

=======
>>>>>>> 2c2ee6de0680a44bc4286d2f5b89ab0fd0fa339d
