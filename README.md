
# How to Install
Restore SunWing database backup file.
Update connection string in WebAPI project and run.
Also update CORS setting in WebAPIConfig.cs under App_Start folder in case Angular client application is running on port other than 4200.
Configure WebAPI URL in Angular app under person.service.ts file under Shared folder.
Run ng serve --open command to run Angular application and perform actions.
