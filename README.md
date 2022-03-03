# java-word-count-beam
## My Name: Padmini Duggirala

## Commands and links I have used

## Links: Java Quickstart : - <https://beam.apache.org/get-started/quickstart-java/>

## Steps:

1. Created a java-word-count-beam folder in the 44517.
2. Executed the commands in the powershell which are mentioned in the java quickstart link.
3. Created a padmini.txt file and copied the text into it.
4. To run the pipeline:

   mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount ` -D exec.args="--inputFile=padmini.txt --output=counts" -P direct-runner
   To inspect the results:  ls counts*
5. Finally, the output file is generated.
