# Gorilla Sessions Tutorial
This project shows two implementations of sessions using the Gorilla Mux library in Go.

The first is a cookie based session system. The second is a filestore based session system.

### Project features
Both of the session implementations hide a secret message behind a type of login system. Users must know the shared `code` to view the message for them. 
An example use case could be a class of students needing a code to view school announcements. 

Without the code you will not be authenticated in the session and redirected away from the secret message. 

### Running the project
Run `go get` to download the gorilla packages needed. 
From either of the two implementation directories using `go run .` to start the server.

Navigate to `localhost:8080` to view the project in your browser. 
