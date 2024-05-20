# Bendarte - Frontend Server.



## Run Complete Project:

### `Auth and Backend Servers:`
- You can find the Auth Server here:
```Auth
https://github.com/bendarte/server-auth.git
```
- You can find the Backend Server here:
```Backend
https://github.com/bendarte/server-backend.git
```

```NOTES
HOW TO RUN COMPLETE PROJECT:
You will have to add the same JWT_SECRET in .env file of the Auth Server & Backend Server.
So the Auth Server can assign JWT to user at login and Backend Server can verify at login.
```

## TTFHW Frontend Server - 5min

### `Frontend Setup:`
- Git clone https://github.com/bendarte/server-frontend.git
- Go to the root folder of the project and run "npm install" in the terminal to get all correct node_modules.

### `How to start the Frontend Server:`
- You can now run "npm start" in the root folder to start the Frontend Server.

#### `Run Complete Project:`
- You will need to add both Auth and Backend Servers to run the complete project.
- Run Frontend Server on PORT=3000
- Run Auth Server on PORT=3001
- Run Backend Server on PORT=3002
- .ENV file in both Auth & Backend Server, both containing the same JWT_SECRET.

