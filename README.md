# java-project-template

An empty Maven project for Java that has plugins setup for coverage, style checking and code quality.

##Selected tools

1. Jacoco - for Java code coverage
2. CheckStyle - for coding conventions checking
3. PMD - for coding smell checks


##Steps to setup IDE

1. Download and install Eclipse - http://www.eclipse.org/downloads/eclipse-packages/
2. Install CheckStyle plugin for Eclipse - http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=150
3. Install EclEmma plugin for Eclipse - http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=264
4. 


mvn archetype:generate 
    -DgroupId=com.dk.samples 
    -DartifactId=java-project-template 
    -DarchetypeArtifactId=maven-archetype-quickstart 
    -DinteractiveMode=false


