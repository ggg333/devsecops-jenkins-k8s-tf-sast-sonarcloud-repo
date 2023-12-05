pipeline {
  agent any
  tools { 
        maven 'Maven_3_5_2'  
    }
   stages{
    stage('CompileandRunSonarAnalysis') {
            steps {	
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=asecgurubuggywebappganesh -Dsonar.organization=asecgurubuggywebappganesh -Dsonar.host.url=https://sonarcloud.io -Dsonar.login=ad10547592dd9bd4216c030d9a9571cf11ae7efd'
			}
        } 
  }
}
