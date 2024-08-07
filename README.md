<div style="display: flex; justify-content: space-between;">
  <p align="center">
    <a href="https://react.dev/" target="blank"><img src="public/react.svg" width="200" alt="React Logo"/></a>
  </p>
  
  <p align="center">
    <a href="https://vitejs.dev/" target="blank"><img src="public/vite.svg" width="200" alt="Vite Logo"/></a>
  </p>

  <p align="center">
    <a href="https://www.typescriptlang.org/" target="blank"><img src="public/typescript.svg" width="200" alt="TypeScript Logo"/></a>
  </p>
</div>

# Buscador de Bebidas - React + Vite + TypeScript + API

Aplicación creada con [React](https://react.dev/), [Vite](https://vitejs.dev/), [TypeScript](https://www.typescriptlang.org/), [TailwindCSS](https://www.npmjs.com/package/tailwindcss), [React Router DOM](https://www.npmjs.com/package/react-router-dom), [Axios](https://www.npmjs.com/package/axios), [ZOD](https://zod.dev/) y [Zustand](https://www.npmjs.com/package/zustand) como manejador global de estado, la Aplicación es un Buscador de Bebidas que se conecta a una API externa, puedes buscar por el nombre de algún ingrediente y por categorías, a demás puedes agregar las recetas a **Favoritos** de manera persistente para que ya no tengas que estar busacdo tus bebidas predilectas. La APP se conecta a la API de [TheCocktailDB](https://www.thecocktaildb.com/), y cuenta con notificaciones personalizadas y uso de Spinners.

Algunos de los conceptos utilizados para la generación de ésta App, son:

1. Formularios.
2. Validaciones.
3. useState.
4. useEffect.
5. useMemo.
6. CSS Modules.
7. Hooks personalizados.
8. [React Router DOM](https://www.npmjs.com/package/react-router-dom).
9. [Axios](https://www.npmjs.com/package/axios).
10. [Zod](https://www.npmjs.com/package/zod).
11. [Zustand](https://www.npmjs.com/package/zustand).
12. Uso de Spinners ([Spinkit](https://tobiasahlin.com/spinkit/)).
13. [heroicons/react][(https://www.npmjs.com/package/@heroicons/react).
14. Y más.


## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
