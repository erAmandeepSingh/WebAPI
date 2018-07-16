
# How to Install
1. Restore SunWing database backup file.
2. Update connection string in WebAPI project and run.
3. Also update CORS setting in WebAPIConfig.cs under App_Start folder in case Angular client application is running on port other than 4200.
4. Configure WebAPI URL in Angular app under person.service.ts file under Shared folder.
5. Run ng serve --open command to run Angular application and perform actions.
