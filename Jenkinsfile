pipeline {
    agent any
    stages {
        stage('-----Maven Clean-----') {
                steps {
                        sh "mvn clean"
			
                }
        }
	 stage('-----Maven Test-----'){
		steps {
			sh "mvn test"
                 }
	    }
        stage('-----Maven Package-----') {
                steps {
			sh "mvn package"
                        }
        }
  }
}

