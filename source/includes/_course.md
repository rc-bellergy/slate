# CourseAction

## Course.getRecord

> Request

```json
{
    "action": "Course",
    "method": "getRecord",
    "data": {
        "id": < int >
    }
}
```

> Response

```json
{
    "result": {
        "data": [ < Course > ],
        "totalCount": < number > ,
        "success": < bool > ,
        "response": {
            "message": < string > ,
            "code": < string >
        }
    }   
}
```

Get Course by course id

### Arguments
course id

### Return
Course

<aside class="notice">
Status: Testing
</aside>