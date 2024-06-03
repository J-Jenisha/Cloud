# Cloud
<h2>Experiment 8</h2>
<p>wget https://repo1.maven.org/maven2/junit/junit/4.13.2/junit-4.13.2.jar</p>
<p>wget https://repo1.maven.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar</p>
<P>javac -cp .:junit-4.13.2.jar:hamcrest-core-1.3.jar src/Calculator.java test/CalculatorTest.java</P>
<P>java -cp .:src:test:junit-4.13.2.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore CalculatorTest</P>


<h2>Experiment 7</h2>
<p>sudo curl -L "https://github.com/docker/compose/releases/download/v2.24.7/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose</p>
<p>sudo chmod +x /usr/local/bin/docker-compose</p>
<p>docker-compose --version</p>

