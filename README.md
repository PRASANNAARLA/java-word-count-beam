# java-word-count-beam

## Prasanna Arla
## Link to java quick start: 
[java quick start](https://beam.apache.org/get-started/quickstart-java/)
## Commands and links that I have used:
1. To generate a Maven project that contains Beam’s WordCount examples and builds against the most recent Beam release:<br> **mvn archetype:generate `
 -D archetypeGroupId=org.apache.beam `
 -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
 -D archetypeVersion=2.36.0 `
 -D groupId=org.example `
 -D artifactId=word-count-beam `
 -D version="0.1" `
 -D package=org.apache.beam.examples 
 -D interactiveMode=false** `</br>
 <br> This will create a word-count-beam directory that contains a pom.xml and several example pipelines that count words in text files. </br>


 2. To Convert from Maven to Gradle Project: **$ gradle init**
3. To Get sample text from Shakespeare: [Shakespeare page](http://shakespeare.mit.edu/allswell/allswell.1.1.html)
4. To Run WordCount Using Maven: **PS> mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner**
 5. To Inspect the results: **$ ls counts***
 
