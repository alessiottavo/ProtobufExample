# ProtobufExample
Repository created in order to test protobuf
### Java
install protoc and then
download protobuf Java runtime .jar file from maven:

    https://mvnrepository.com/artifact/com.google.protobuf/protobuf-java

Then run the following:

    $ export CLASSPATH=/path/to/protobuf-java-[version].jar
    $ make java

This will create the add_person_java/list_people_java executables (shell
scripts) and can be used to create/display an address book data file.
