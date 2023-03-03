# Go REST API

This is a simple REST API written in Go. It is a simple program to understand the basics of Go programming and Gin framework for building REST APIs.

`go run main.go` or `./main`

Access the API at `http://localhost:8080/albums` to get the list of albums (3 in this case)

Access the API at `http://localhost:8080/albums/1` to get the details of the album with ID 1

You can use POST method to add a new album. The body of the request should be in JSON format. For example:

`curl -X POST -H "Content-Type: application/json" -d '{"Title":"New Album","Artist":"New Artist","Price":10.99}' http://localhost:8080/albums`

Enjoy!
