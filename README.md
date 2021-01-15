# React hook to execute callback when a click is happened outside of component.

# Install
yarn add use-click-outside-click

# Usage 

### `import React, { useRef } from 'react';`
`import useClickOutside from 'use-click-outside-click';`
 
`const Modal = ({ onClose }) => {`
 ` const ref = useRef();`
 ` useClickOutside(ref, onClose);`
 
  `return <dialog ref={ref}>Hello, World!</dialog>;`
};`