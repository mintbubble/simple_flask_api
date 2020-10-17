# simple_flask_api
`curl -i http://127.0.0.1:5000/todo/api/v1/tasks`
`curl -i http://127.0.0.1:5000/todo/api/v1/tasks/1`
`curl -i -H "Content-Type: application/json" -X POST -d"{"""title""":"""Test"""}" http://127.0.0.1:5000/todo/api/v1/tasks`
`curl -i -H "Content-Type: application/json" -X PUT -d"{"""title""":"""Test_UPDATE1"""}" http://127.0.0.1:5000/todo/api/v1/tasks/1`
`curl -i -H "Content-Type: application/json" -X DELETE http://127.0.0.1:5000/todo/api/v1/tasks/2`