## slugify-now

A minimal, fast, and zero-dependency slugify function to convert strings into URL-safe slugs.

---

## Install

```bash
npm install slugify-now
```

---

## Usage

```javascript
import slugify from 'slugify-now';

const title = "Hello World! I'm Inkersal";
const slug = slugify(title);

console.log(slug); // "hello-world-im-inkersal"
```

#### `Typescript Usage`
```typescript
slugify(text: string): string
```

---

## Features
- Converts to lowercase
- Removes accents and special characters
- Replaces non-alphanumerics with `-`
- Trims extra dashes

---

## Examples

|           Input                |          Output              |
|--------------------------------|------------------------------|
| `React & Node.js Crash Course` | `react-node-js-crash-course` |
| `Éléphant Café`                | `elephant-cafe`              |
| `   spaced out   `             | `spaced-out`                 |