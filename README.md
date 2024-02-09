# Bendarte - Frontend Server.

![project_structure](https://private-user-images.githubusercontent.com/143492796/302132105-2c80134b-a563-4336-a62e-9566d87b3d77.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDc0OTg1NzksIm5iZiI6MTcwNzQ5ODI3OSwicGF0aCI6Ii8xNDM0OTI3OTYvMzAyMTMyMTA1LTJjODAxMzRiLWE1NjMtNDMzNi1hNjJlLTk1NjZkODdiM2Q3Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMjA5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDIwOVQxNzA0MzlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xZmYwMWFjNzI5OGRkOWY2Zjg1NDY4MjI4OTBhNzhkODFhMzc5YTNjNjRlMGJlNDE2OGU1NDZlNTNiMGU3NzJmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.cWpMmbumrZFuo3WtbchOd_WQuO9osZRwVux5IhWk5YI)

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

