# git-commit-id-heroku-demo
A spring boot app deployed to heroku which displays git-commit-id plugin details.

## To run locally

Use this command to build the project

```
mvn clean package -DskipTests=true
```

and this to run the application in a manner simular to heroku

```
java -jar ./target/git-id-heroku-demo-0.0.1-SNAPSHOT.jar
```