# Introduction


# Getting Started
to run this service
```
> go build
> ./user-microservice.exe
```

to execute API
```
curl -X POST http://127.0.0.1:8808/api/v1/admin/auth -F 'user=admin' -F 'password=admin'
```

## Error knowledge
### Run swag init
Run swag init with a error
```
> swag init
swag : The term 'swag' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path   
is correct and try again.
```

To fix it
```
Move swag.exe from C:/go/bin/bin to C:/go/bin
```
