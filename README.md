Server.js -> containing server configurations to listen to the HTTP requests and route the requests
userRouter and empRouter both created to route the requests received using express.Router() and send appropriate responses
userRouter -> /api/v1/user/...
empRouter -> /api/v1/emp/...

run `nopm install` to install the required modules for the code to build and have fun with it!
The connection to MongoDB uses a secondary user on my account -> "john123:john12345" -> the user does not have administrative privileges but can read and write to comp3123_assignment1 database
