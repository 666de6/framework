# `throwError`

Nuxt provides a quick and simple way to throw errows.

Within your pages, components and plugins you can use `throwError` to throw an error.

**Parameters:**

- `error`: `string | Error`

```js
throwError("😱 Oh no, an error has been thrown.")
```

The thrown error is set in state using [`useError()`](/api/composables/useError) to create a reactive and SSR-friendly shared error state across components.

`throwError` calls the `app:error` hook.

::ReadMore{link="/guide/features/error-handling"}
::
