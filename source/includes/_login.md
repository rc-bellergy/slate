# LoginAction

## Login.login

> Request

```json
{
    "action": "Login",
    "method": "login",
    "data": < User >
}
```

> Response

```json
{
    "result": {
        "data": [ < User > ],
        "success": < bool > ,
        "response": {
            "message": < string > ,
            "code": < string >
        }
    }
}
```

User login

### Arguments
User

### Return
User

<aside class="notice">
Status: Testing
</aside>


## Login.logout

> Request

```json
{
    "action": "Login",
    "method": "logout",
    "data": {}
}
```

> Response

```json
{
    "result": {
        "data": {
            "id": < int >
        }
        "success": < bool > ,
        "response": {
            "message": < string > ,
            "code": < string >
        }
    }
}
```

User logout
### Arguments
null

### Return
null

<aside class="notice">
Status: Testing
</aside>


## Login.sendResetPasswordEmail

> Request

```json
{
    "action": "Login",
    "method": "sendResetPasswordEmail",
    "data": { }
}
```

> Response

```json
{
    "result": {
        "data": { }
        "success": < bool > ,
        "response": {
            "message": < string > ,
            "code": < string >
        }
    }
}
```

Send reset password email to user
### Arguments
null

### Return
null

<aside class="notice">
Status: Defined
</aside>



## Login.sendActivationEmail

> Request

```json
{
    "action": "Login",
    "method": "sendActivationEmail",
    "data": { }
}
```

> Response

```json
{
    "result": {
        "data": { }
        "success": < bool > ,
        "response": {
            "message": < string > ,
            "code": < string >
        }
    }
}
```

Send reset activation email to user
### Arguments
null

### Return
null

<aside class="notice">
Status: Defined
</aside>
