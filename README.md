# gretljobs

```
export ORG_GRADLE_PROJECT_dbUriOereb=jdbc:postgresql://localhost:54323/oereb
export ORG_GRADLE_PROJECT_dbUserOereb=gretl
export ORG_GRADLE_PROJECT_dbPwdOereb=gretl
export ORG_GRADLE_PROJECT_awsAccessKeyAgi=XXXX
export ORG_GRADLE_PROJECT_awsSecretAccessKeyAgi=YYYY


```


```
gradle tasks --all --no-daemon -Dorg.gradle.jvmargs=-Xmx2G --init-script ../init.gradle
```