#### Use the following API
#### https://jsonplaceholder.typicode.com/
- use a similar schema and pass required fields in your request

```js
    {
    "userId": 1,
    "id": 1,
    "title": "delectus aut autem",
    "completed": false
    }
```
#### Make a post request using the /todos endpoint
- Request:
```js
    curl -X POST --header "Content-Type:application/json" -d "{\"userId\": \"1\",\"title\":\"delectus aut autem\",\"completed\":\"false\",\"body\":\"Content\" }" https://jsonplaceholder.typicode.com/todos
```
- Response:
```js
    {
    "userId": "1",
    "title": "delectus aut autem",
    "completed": "false",
    "body": "Content",
    "id": 201
    }
```
#### explicit flag ( which means use -X )
- Request:
```js
    curl -X POST --header "Content-Type:application/json" -d "{\"userId\": \"1\",\"title\":\"delectus aut autem\",\"completed\":\"false\",\"body\":\"Content\" }" https://jsonplaceholder.typicode.com/todos
```
- Response:
```js
    {
    "userId": "1",
    "title": "delectus aut autem",
    "completed": "false",
    "body": "Content",
    "id": 201
    }
```