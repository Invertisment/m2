# A maven repo

### Usage for gradle projects:

- open your project
- `gradle clean`
- `gradle fatJar` or `gradle jar`
- Do maven jar install step

### Usage for maven projects:
`https://gist.github.com/cleberjamaral/6c9b0a615e51e26c94ffe407a641f531`

### Packages

_Agora token creation lib_
`https://github.com/AgoraIO/Tools/tree/master/DynamicKey/AgoraDynamicKey/java`
Install command used:

```
gradle clean
gradle jar
mvn install:install-file -DgroupId=io.agora -DartifactId=authentication -Dversion=1.6.1 -Dfile=./links/AgoraIOTools/DynamicKey/AgoraDynamicKey/java/target/authentication-1.6.1.jar -Dpackaging=jar -DlocalRepositoryPath=. -DcreateChecksum=true -DgeneratePom=true
```
