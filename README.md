# RestApis
with using Node, Express, Typescript, Mongodb

# Step
Update mongodb url in MONGO_URL [src/index.ts]

```bash
npm install
```
Run Server http://localhost:8080/
```bash
npm start
```
Rest apis 
## Register
Method: POST
URL:  http://localhost:8080/auth/register
Data: {
    email: test@test.com
    password: test1234
    username: test
}

## Login
Method: POST
URL:  http://localhost:8080/auth/login
Data: {
    email: test@test.com
    password: test1234
}
