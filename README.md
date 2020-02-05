<head>
	<h1>  GoStack - FASTFEET API</h1>
</head>
<body>
	<p align="center">
  <img src="logo.png" width="350" title="Go Barber">
</p>
<div>
  
  ##  Description:  
   - This project is a barber shop system where services are scheduled, customers and service providers login and listings, notifications are also displayed and email is sent.
   
  ##  Running:  
   - Clone code - "git clone url_repository" .
   - Running "yarn" in path .
   - Create instances docker: 
        - `Postgres:` docker run --name INSTANCE_NAME -e POSTGRES_PASSWORD=PASS -p 5432:5432 -d postgres:11
        - `MongoDB:` docker run --name INSTANCE_NAME -p 27017:27017 -d -t mongo
        - `Redis:` docker run --name INSTANCE_NAME -p 6379:6379 -d -t redis:alpine
   - For better structuring of the code used, such as editor, editor configuration and deletion, installation of plugins in Vscode.
   
   - Create an .env file from .envexample
   
   - run "yarn dev" in terminal and "yarn queue" in another.
   
   - In insomnia import workspace file "Insomnia_request_test.json"
  
   ##  Technologies Used:
   - Express  
   - NodeMailer
   - Multer
   - JWT
   - DotEnv
   - Bcrypt
   - Yup
   - Mongoose
   - Sequelize
   - Bee-Queue
   - Database: 
        - `Postgres` - Structured Data
        - `MongoDB`  - Unstructured data / notification control
        - `Redis`    - Queue control for sending email
   - Developer:
        - `Eslint`
        - `Prittier`
        - `Editor Config`
        - `Sentry`
        - `Sucrase`
        - `Nodemon`
   
     
  
  ## Features:
  - Login/Create/Update User using JWT
  - Create/Liste/Delete Appointments
  - List/Update Notifications
  - Send Email Notifications
  - List Schedule provider
  - List Available hours
  - List Provider
  - Upload Avatar Image
   
</div>

</body>

<footer>
  <p>Mário Wessen - <a href="mailto:mariowessen@gmail.com">mariowessen@gmail.com</a></p>
</footer>




