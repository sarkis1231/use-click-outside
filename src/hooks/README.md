> React hook to execute callback when a click is happened outside of html element.

## Install

```sh
yarn add use-click-outside-close
```

## Usage

```jsx
import React, { useRef } from 'react';
import useClickOutside from 'use-click-outside';

const Modal = ({ onClose }) => {
  const ref = useRef();
  useClickOutside(ref, onClose);

  return <div ref={ref}>Hello, World!</div>;
};
```

Or if you need a custom event type instead of default 'click', third parameter can be passed:

```js
  useClickOutside(ref, handler);
```

## Show your support

Give a ⭐️ if this project helped you!
