# Gateway Gradle Demo

A sample gradle project using Spring Cloud Gateway extensions.

## Requirements

A `~/.gradle/gradle.properties` file must be populated with:
```
broadcomJFrogArtifactoryHost=<host>
broadcomJFrogArtifactoryUsername=<username>
broadcomJFrogArtifactoryPassword=<password>
```

## Running

The app requires the Tanzu Local Authorization Server. You can run this using `scripts/tanzu-auth-server.sh`.

When running the Demo Application, accessing
http://localhost:8080/test/get will redirect you to SSO.

You can log in with user/password: `test` / `test`.
