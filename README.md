# Cloud

<p>wget https://repo1.maven.org/maven2/junit/junit/4.13.2/junit-4.13.2.jar</p>
<p>wget https://repo1.maven.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar</p>
<P>javac -cp .:junit-4.13.2.jar:hamcrest-core-1.3.jar src/Calculator.java test/CalculatorTest.java</P>
<P>java -cp .:src:test:junit-4.13.2.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore CalculatorTest</P>

