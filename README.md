# SvelteKit Snippets

This Extension adds snippets for SvelteKit.

## Features

Snippets for `javascript`.

Example:

`$import` will expand to:

```js
import {} from "@sveltejs/kit";
```

`$get` will expand to:

```js
/** @type {import('./$types').RequestHandler} */
export function GET(event) {
	return json({});
}
```

`$pagedata` will expand to:

```js
/** @type {import('./\\$types').PageData} */
export let data;
```

**Many other snippets like:**

`$import`, `$get`, `$post`, `$patch`, `$put`, `$delete`, `$pagedata`, `$layoutdata`, `$environment`, `$forms`, `$navigation`, `$paths`, `$stores`, `$envstaticpublic`, `$envstaticprivate`, `$envdynamicpublic`, `$envdynamicprivate`, `$serviceworker`, `$hooks`, `$node`, `$polyfills`, `$vite`, `$lib`, `$internal`

## Release Notes

### 0.0.2

Better documentation on README.md

### 0.0.1

Initial release of Svelte Snippets by MrAmericanMike

---

## Requests - Ideas

Do you have a request or idea for the extension. Please post it on our [Discussion Board](https://github.com/MrAmericanMike/sveltekitsnippets/discussions) on GitHub

---

## Pending features

Determine if it's possible for a snippets extension to have a configuration option and use it so the final user can decide if they want single or double quotes

---

**Enjoy!**

