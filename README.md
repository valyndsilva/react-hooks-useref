# useRef Hook Tutorial

Important Rules To Remember about useRef Hooks:

1. In useRef hook the value persists (stays the same between renders).
2. Updating the reference does not trigger a re-render.

When we update the state, useState triggers a re-render of the component.
When we update the ref, useRef does not trigger a re-render of the component.

useRef can help get access to DOM elements but this is not recommended when using react.
Only use useRef to create a reference to something within your component when you need to access it. Ex: setting a focus.
