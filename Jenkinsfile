pipeline {
    agent any
	
	environment {
	    APP_NAME = "HelloCI"
	}

    stages {
        stage('Build') {
		    steps {
			    bat "echo Building %APP_NAME%"
			}
		}
	}
}	