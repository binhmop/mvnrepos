# mvnrepos
Add this GitHub repository to the POM file:

    <repositories>
        <repository>
            <id>bhan-releases</id>
        	<name>github-hosted repo for released jars</name>
        	<url>https://github.com/binhmop/mvnrepos/raw/master/releases/</url>
        </repository>
        <repository>
            <id>bhan-snapshots</id>
        	<name>github-hosted repo for snapshot jars</name>
        	<url>https://github.com/binhmop/mvnrepos/raw/master/snapshots/</url>
        </repository>
    </repositories>
