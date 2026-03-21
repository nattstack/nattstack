```jsx
// bun add @nattstack/ui
// bun add @nattstack/tailwind-colors
// bun add @nattstack/tailwind-exact

// global.css
@import "tailwindcss";
@import "@nattui/tailwind-colors";
@import "@nattui/tailwind-exact";

// component.tsx
import { Button, Input, Label } from "@nattstack/ui/react"

<Label className="mb-2" htmlFor="email">
  Email
</Label>
<Input
  autoComplete="email"
  className="mb-16"
  id="email"
  isRequired
  name="email"
  type="email"
/>
<Button type="submit">
  Sign in
</Button>
```

- [ui](https://react-components-web.vercel.app)
- [config-and-setup-notes](https://github.com/nattstack/config-and-setup-notes)

