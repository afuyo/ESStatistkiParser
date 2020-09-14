# xmlparser
Java / Kotlin app able to process huge xml files.
 Currently it process dansk motorregister(DMR) 80GB XML-file under 19 minutes. 

# Build
Run gradle `jar` build task

# Run
DMR file is provided by Danish Tax Authorities. You can use the sample file 
and then point it in the command run:

`java -jar build/libs/xmlparser-1.0.0.jar file-path=test10.xml.gz file-name=test10.xml job-chunk-size=10`
