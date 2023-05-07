# SvelteKit Snippets

This Extension adds snippets for SvelteKit.

## Features

Snippets for `javascript` and `typescript`.

Example:

`$import` will expand to:

```js
import {} from "@sveltejs/kit";
```

`$get` in Javascript will expand to:

```js
/** @type {import("./$types").RequestHandler} */
export function GET(event) {
	return json({});
}
```

`$get` in Typescript will expand to:

```ts
export const GET = ((event) => {
	return json({});
}) satisfies RequestHandler;
```

`$pagedata` in Javascript will expand to:

```js
/** @type {import("./$types").PageData} */
export let data;
```

`$pagedata` in Typescript will expand to:

```ts
import type { PageData } from "./$types";
export let data: PageData;
```

**Many other snippets like:**

`$import`, `$get`, `$post`, `$patch`, `$put`, `$delete`, `$pageload`, `$pageserverload`, `$pagedata`, `$layoutload`, `$layoutserverload`, `$layoutdata`,, `$actions`, `$handle`, `$handlefetch`, `$handleservererror`, `$handleclienterror`, `$environment`, `$forms`, `$navigation`, `$paths`, `$stores`, `$envstaticpublic`, `$envstaticprivate`, `$envdynamicpublic`, `$envdynamicprivate`, `$serviceworker`, `$hooks`, `$node`, `$polyfills`, `$vite`, `$lib`, `$internal`

## Release Notes

### 0.0.4

Fixed example on documentation
Added `$actions`, `$handle`, `$handlefetch`, `$handleservererror`, `$handleclienterror`, `$layoutload`, `$layoutserverload`
Added hints in snippets descriptions about in what files each snippet "should" be used most commonly (When applicable)

### 0.0.3

Fixed minor error on documentation
Added Issues Tracker to the documentation
Added basic support for TypeScript

### 0.0.2

Better documentation on README.md

### 0.0.1

Initial release of Svelte Snippets by MrAmericanMike

---

## Requests - Ideas

Do you have a request or idea for the extension. Please post it on our [Discussion Board](https://github.com/MrAmericanMike/sveltekitsnippets/discussions) on GitHub

## Issues

Please report any issues on GitHub [Issues Tracker](https://github.com/MrAmericanMike/sveltekitsnippets/issues)

---

## Pending features

Determine if it's possible for a snippets extension to have a configuration option and use it so the final user can decide if they want single or double quotes

---

