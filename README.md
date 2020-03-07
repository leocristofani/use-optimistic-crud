# useOptimisticCRUD

A custom React hook that performs CRUD operations optimistically

### Install

`npm install --save use-optimistic-crud`

### How to use it

```
const {users, error, loading, create, update, delete} = useOptimisticCRUD(
  "https://baseurl.com/api/users",
  { /* query params go here */ }
);
```
