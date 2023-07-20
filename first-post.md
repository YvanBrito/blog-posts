# My first Post

This is my first post in my blog. This is a great achievement to me because with this blog I am able to:

- Describe my previuos experiences;
- Learning something new to me and shared this new knowledge
- Share some news that I find interisting and etc.

You are welcome to send me some email (yvanbrito96@gmail.com) with any comments about my next posts. Greetings!!!

This is a piece of code for test

```typescript
import { createRoot } from 'react-dom/client';

interface HelloMessageProps {
  name: string
}

function HelloMessage({ name }: HelloMessageProps) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
