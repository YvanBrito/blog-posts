# My First Post

This is my first post on my blog, and it feels like a great achievement to me. With this blog, I am able to:

1. Describe my previous experiences.
2. Learn something new and share this newfound knowledge.
3. Share some interesting news, and more.

You are welcome to send me an email (`yvanbrito96@gmail.com`) with any comments about my upcoming posts. Greetings!

---

```jsx
import { createRoot } from 'react-dom/client';

interface HelloMessageProps {
  name: string;
}

function HelloMessage({ name }: HelloMessageProps) {
  return &lt;div&gt;Hello {name}&lt;/div&gt;;
}

const root = createRoot(document.getElementById('container'));
root.render(&lt;HelloMessage name="Taylor" /&gt;);
```
