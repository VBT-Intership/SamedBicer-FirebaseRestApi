# Firebase RESTful API Example

Basic Firebase RESTful API Example that you can perform GET, POST, PUT, PATCH and DELETE requests.

## Usage
Execute the command below from the Command Line

### Perform an HTTP GET Request
```bash
curl https://firstproject-c81e7.firebaseio.com/users.json
```

### Perform an HTTP POST Request
```bash
curl -d '{"name": "samed_bcr","email": "sammy@gmail.com"}' \
-X POST https://firstproject-c81e7.firebaseio.com/users.json
```

### Perform an HTTP PUT Request
```bash
curl -d '{"name": "jack","email": "jack@gmail.com"}' \
-X PUT https://firstproject-c81e7.firebaseio.com/users/-MFLfBPW9O9d2ZEQ59fv.json
```

### Perform an HTTP PATCH Request
```bash
curl -d '{"name": "sammy","email": "sammy@gmail.com"}' \
-X PATCH https://firstproject-c81e7.firebaseio.com/users/-MFLfBPW9O9d2ZEQ59fv.json
```

### Perform an HTTP DELETE Request
```bash
curl -X DELETE https://firstproject-c81e7.firebaseio.com/users/-MFLfBPW9O9d2ZEQ59fv.json
```