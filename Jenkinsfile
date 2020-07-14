pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            sh "echo 'shell scripts to build project...'"
        }

        stage ('Testing Stage') {

            parallel 'static': {
	            sh "echo 'shell scripts to run static tests...'"
	        },
	        'unit': {
	            sh "echo 'shell scripts to run unit tests...'"
	        },
	        'integration': {
	            sh "echo 'shell scripts to run integration tests...'"
	        }
        }


        stage ('Deployment Stage') {
            sh "echo 'shell scripts to deploy to server...'"
        }
    }
}
