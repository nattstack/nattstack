```jsx
// bun add @nattui/react-components
// bun add @nattui/tailwind-colors
// bun add @nattui/tailwind-exact

// global.css
@import "tailwindcss";
@import "@nattui/tailwind-colors";
@import "@nattui/tailwind-exact";

// component.tsx
import { Button, Input, Label } from "@nattui/react-components"

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

- [react-components](https://react-components-web.vercel.app)
- [config-and-setup-notes](https://github.com/nattui/config-and-setup-notes)

I have around 2000 additional commits from my other account this past year.
