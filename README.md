The purpose of this project to sort of "torture" Java records in various ways.

Please be aware, that the usage you find in the sources is not always the recommended way of using records in real, production code.

This projects shows what _can_ be done with records, not _should_ be done with records.

To run sample with Lombok, you can use:

    MAVEN_OPTS="--enable-preview" mvn package exec:java -Dexec.mainClass="dev.softwaregarden.records.torture.lombok.LombokAndRecordsCheck"