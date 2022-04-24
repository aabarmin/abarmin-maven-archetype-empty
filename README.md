# ABarmin Apache Maven Archetype (empty)

Archetype to create new empty projects. This archetype provides up to date versions of plugins.

After the repository is cloned, execute `./mvnw clean install` to install the archetype to the local Apache Maven registry.

To generate a new project using this archetype execute the following command:

```shell
$ mvn archetype:generate \
    -DarchetypeArtifactId=archetype-empty \
    -DarchetypeGroupId=dev.abarmin.archetype
```
