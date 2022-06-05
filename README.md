# go-movies-crud
Simple CRUD API using Go

The API structure :
```
GET  /movies                    # return all movies
POST /movies                    # add a new movies
GET /movies/{id}                # get specific movie based on id
DELETE /movies/{id}             # delete movie based on id
PUT /movies/{id}                # update movie based on id
```

## Run 🛠
> All commands are to be run from the root project directory.
> 
> This project uses Go version `1.18`.
> 
> Current `go` executables should detect and install dependencies correctly.


To start :
1. Open Windows Powershell and go to the project directory. Execute `go run main.go`
2. Powershell will show `Starting server at port 8000`
3. Go to browser, navigate to `locahost:8000`
