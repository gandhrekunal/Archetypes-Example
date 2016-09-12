Create a project
----------------

```bash
    mvn archetype:generate \
        -DarchetypeGroupId=com.example \
        -DarchetypeArtifactId=testapp-quickstart-archetype \
        -DarchetypeVersion=1.0.0.0 \
        -DgroupId=my.groupid \
        -DartifactId=my-artifactId \
        -Dversion=version \
        -DarchetypeRepository=https://github.com/testapp-quickstart-archetype
```

Example

```bash
mvn archetype:generate -DarchetypeGroupId=com.example -DarchetypeArtifactId=testapp-quickstart-archetype -DarchetypeVersion=1.0.0.0-SNAPSHOT -DgroupId=my.com -DartifactId=KunalApp -Dversion=1.0
```