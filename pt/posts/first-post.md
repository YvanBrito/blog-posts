# Minha primeira postagem

![Javascript code](https://raw.githubusercontent.com/YvanBrito/blog-posts/main/assets/img/jscode01.jpeg)

Esta é minha primeira postagem no meu blog e é grande conquista para mim. Com este blog, vou:

1. Descrever minhas experiências anteriores.
2. Aprender algo novo e compartilhar esse conhecimento recém-adquirido.
3. Compartilhar algumas notícias interessantes e muito mais.

Você pode me enviar e-mails (`yvanbrito96@gmail.com`) com quaisquer comentários sobre minhas próximas postagens. Saudações!

```jsx
import { createRoot } from 'react-dom/client';

interface HelloMessageProps {
  name: string;
}

function HelloMessage({ name }: HelloMessageProps) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
