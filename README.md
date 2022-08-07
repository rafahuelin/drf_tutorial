### Test api
```
curl -H 'Accept: application/json; indent=4' -u admin:password123 http://127.0.0.1:8000/users/
```
#### Response
```
{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "url": "http://127.0.0.1:8000/users/1/",
            "username": "admin",
            "email": "admin@example.com",
            "groups": []
        }
    ]
}
```

### Or visiting the url
http://127.0.0.1:8000/users/

