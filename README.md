# my-protected-web-api
 This is a genererated Web API wich runs on a Node.js server and uses MongoDB data.

 WARNING: Before proceeding to [Instalation](#Instalation) check the [config.js](config.js) file located in the root of the project.

 ## Table of Contents
 * [Instalation](#Instalation)
 * [Usage](#Usage)
	 * [Token](#Token)
	 * [Users](#Users)

 ## Instalation
 Install the modules
 ```
 npm install
 ```
 Start the server
 ```
 npm start
 ```

 ## Usage

 #### Token
 Authenticate using the following endpoint with credentials set in [config.js](config.js) file.
 ``` 
 POST /login 
 ```
 You will get a bearer token to use in the Authorization header for API requests.
 
 #### Users
 |HTTP Method|Path | Path Params | Query Params | Body Params |
 |:-------------:|-------------|:-------------:|:-------------:|:-----:|
 |GET| /api/users|None|None|None|
 |GET| /api/users/{id}|Id|None|None|
 |POST| /api/users|None|None|Collection Schema|
 |PUT| /api/users/{id}|Id|None|Collection Schema|
 |DELETE| /api/users/{id}|Id|None|None|