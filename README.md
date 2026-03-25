```tsx
// bun add @nattstack/ui

// global.css
@import "tailwindcss";
@import "@nattstack/ui/tailwind-colors";
@import "@nattstack/ui/tailwind-tokenless-10";

// component.tsx
import { Button, Input, Label } from "@nattstack/ui"

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

