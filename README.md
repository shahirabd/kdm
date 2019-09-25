# kdm
Kaodim Assessment - Postman test

Instructio

Run locally using Postman
1. Download the collection and the environment file to your local drive. Save them in the same folder.
2. Open Postman App on your desktop
3. Import the collection
4. Then run the test using the collection runner, by selecting the "Kaodim" environment.

Alternatively run the test by clicking this button - [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/84b99679bd0eeadc788c#?env%5BKaodim%5D=W3sia2V5IjoiaG9zdCIsInZhbHVlIjoibXkuc3VwcG9ydC5rYW9kaW0uY29tL2FwaS92MSIsImVuYWJsZWQiOnRydWV9XQ==)

Run locally using CLI
1. Download the collection and the environment file to your local drive. Save them in the same folder.
2. Make sure you have 'newman' and it's pre-requisite installed. Link: https://www.npmjs.com/package/newman
3. Open command prompt, go to the location where you downloaded the collection on step 1. Eg: "cd C:\users\username\documents\Postman Tests"
4. Enter this line: newman run "Kaodim Assessment.postman_collection.json" -e "Kaodim.postman_environment.json" -r cli,json
