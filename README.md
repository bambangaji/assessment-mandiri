

## How To Run This project
run `npm install` in the root directory
run `ng serve` to run dev server

## Information
This app using angular material to using the datepicker, u can see the document https://material.angular.io/
Style framework using bootstrap u can see the document https://getbootstrap.com/docs/5.3/getting-started/introduction/

in environment.ts u can store global key like base API URL
## Build
run `ng build` to build this project into web and location in dist folder in the application root directory with all the files that a hosting service needs for serving your application.

## Global management state 
for ui
-- edit in services/ui/ui.service.ts u can add like bottomsheet,loading,etc
for config
-- edit in servicse/config/config.service.ts

# Environtment 
`apiUrl` for base API

# Service
For routing service u must edit in
Services/routing/routing.service.ts
add function routing in this file 

# Flow Cycle This Project
-- Hit API
 1. create function to hit api in services/api/api.service
 2. create function to call the function u create before in ur model example : models/user/employee-model.ts
 3. now u can manipulate data from API
