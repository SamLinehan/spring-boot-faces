## JavaServer Faces with Spring Boot

To run: 
- `mvn clean install`
- `mvn spring-boot:run`

To debug in VSCode:
- First, run `mvnDebug spring-boot:run -Dagentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=8000` in your terminal. This will start the application in debug mode.
- Next, go to the `Run` tab in VSCode. Next to the green Play button, select `Debug (Attach)` and press the Play button. This will attach the debugger to the running process in your terminal.
- Finally, add some breakpoints and go to `localhost:8080`