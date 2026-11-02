# expo-require-utils-bun-typescript-7

`npx create-expo-app@latest --template blank`, with `app.json` read through a typed `app.config.ts` and `typescript@7.0.2` as the only TypeScript.

```sh
bun install
bun --bun expo config --type public   # SyntaxError: Unexpected identifier 'type'
npx expo config --type public         # prints the config
```

With `typescript@6.0.3` in its place, `bun --bun expo config --type public` prints the config too.
