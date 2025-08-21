# flowbite-svelte-admin-dashboard

- [demo](https://flowbite-svelte-admin-dashboard.vercel.app/)
- [repo](https://github.com/themesberg/flowbite-svelte-admin-dashboard)

## Installation

```bash
# create a new project in my-app
# install tailwindcss
npx sv create my-app
cd my-app
pnpm i -D flowbite-svelte-admin-dashboard
# it's a good idea to update all dependencies
pnpm update
# run the server
pnpm dev
```

## Liquid glass panel

This project provides a `LiquidGlassPanel` component powered by [`liquid-glass-svelte`](https://www.npmjs.com/package/liquid-glass-svelte).

```svelte
<script lang="ts">
  import { LiquidGlassPanel } from 'flowbite-svelte-admin-dashboard';
</script>

<LiquidGlassPanel>
  <h1>Your dashboard</h1>
</LiquidGlassPanel>
```
