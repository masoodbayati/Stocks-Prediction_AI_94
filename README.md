# Stocks-Prediction_AI_94
This is a project to predict the stock and if you want to use it just change the input directory by your self and run the project.

#Prerequisites:

1.Linux or Mac

2.Java 1.3

3.Apache Maven 3

#How to run:
there is two way to run this project:

**first:**
1. download the project.
2. open the neuralNetwork directory in terminal
3. use this command for run the project:

mvn compile

mvn exec:java -Dexec.mainClass="com.technobium.NeuralNetworkStockPredictor"

and if you have problem you can follow the second way

**second:**

1. download the project.
2. use the following command to create new project:

mvn archetype:generate \
-DarchetypeGroupId=org.apache.maven.archetypes \
-DgroupId=com.technobium \
-DartifactId=neuralNetwork \
-DinteractiveMode=false

3.and after that use this command:

mv neuralNetwork/src/main/java/com/technobium/App.java \
neuralNetwork/src/main/java/com/technobium/NeuralNetworkStockPredictor.java

4. replace the the src directory,input directory and pom.xml with the project you download.
5. and at last use this command to run:

mvn compile
mvn exec:java -Dexec.mainClass="com.technobium.NeuralNetworkStockPredictor"


#Notice:
Notice that dont rely on this project in real deals . 
