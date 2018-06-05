# Models

## User

> Admin.model.User

```js
[
    { name: 'userId', type: 'int' },
    { name: 'username', type: 'string' },
    { name: 'password', type: 'string' }, 
    { name: 'firstname', type: 'string' },
    { name: 'lastname', type: 'string' },
    { name: 'roles', type: 'auto' } // ['administrator', 'operator']
]
```
