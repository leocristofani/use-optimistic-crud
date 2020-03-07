# useOptimisticCRUD

A custom React hook that performs CRUD operations optimistically. Meaning, it does NOT wait for the server to respond in order to update local state, giving end users perception of immediate change.

### Install

`npm install --save use-optimistic-crud`

### How to use it

```js
const { users, error, loading, create, update, delete } = useOptimisticCRUD(
  "https://baseurl.com/api/users",
  {
    /* query params go here */
  }
);
```
