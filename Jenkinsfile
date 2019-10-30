pipeline{
agent any
stages{
	stage('build'){
		steps{
			sh'/usr/share/maven/bin/mvn clean install'
		}
	}
	stage('Test'){
		steps{
			sh'/usr/share/maven/bin/mvn test'
		}
	}
}
