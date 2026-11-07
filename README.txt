MS1 - MockMvc Controller Unit Testing

Requirements:
- JDK 17 or later
- STS4 / Eclipse with Spring Tools and Maven support

Import into STS4 / Eclipse:
1. Extract this ZIP file.
2. Open STS4 / Eclipse.
3. Select File > Import > Maven > Existing Maven Projects.
4. Browse to the extracted MS1-MockMvc-Project folder.
5. Select the pom.xml and click Finish.
6. Wait for Maven dependencies to download.

Run the unit test:
1. Expand src/test/java.
2. Open com.example.demo > MS1ControllerTest.java.
3. Right-click the file > Run As > JUnit Test.
4. Expected: 1 test, 0 failures, 0 errors.

Expected test response:
HTTP 200 OK
MS 1.1 - Additon = 15

Optional: Run the application:
Right-click Ms1Application.java > Run As > Spring Boot App.
Then open:
http://localhost:8080/ms1/add?a=5&b=10

Expected browser response:
MS 1.1 - Additon = 15

Note:
The MockMvc unit test does not require starting the full web server.
