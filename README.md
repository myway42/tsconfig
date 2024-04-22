[![NPM Version](https://img.shields.io/npm/v/%40myway42%2Ftsconfig)](https://www.npmjs.com/package/@myway42/tsconfig)

# tsconfig

Add the package to your `"devDependencies"`:

```sh
npm install --save-dev @myway42/tsconfig
```

Add to your `tsconfig.json`:

```json
"extends": "@myway42/tsconfig/tsconfig.json"
```

---

The `tsconfig.json`:

```jsonc
{
  "compilerOptions": {
    "target": "ES6",
    "module": "ESNext",
    "useDefineForClassFields": true,
    "skipLibCheck": true,
    /* Bundler mode */
    "moduleResolution": "Bundler",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true,
    /* Linting */
    "strict": true
  },
  "$schema": "https://json.schemastore.org/tsconfig"
}
```
