# ddd-mvn-archetype

Generate archetype:
    
    mvn archetype:generate                                \
    -DarchetypeGroupId=<archetype-groupId>                \
    -DarchetypeArtifactId=<archetype-artifactId>          \
    -DarchetypeVersion=<archetype-version>                \
    -DgroupId=<my.groupid>                                \
    -DartifactId=<my-artifactId>
    
Example:

    mvn archetype:generate                                \
    -DarchetypeGroupId=tao                \
    -DarchetypeArtifactId=ddd-mvn-archetype          \
    -DarchetypeVersion=1.0-SNAPSHOT                \
    -DgroupId=tao                                \
    -DartifactId=sample 