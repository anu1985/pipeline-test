pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
            steps {
            sh "echo 'shell scripts to build project...'"
            }
        }

        stage ('Testing Stage') {
            steps {
               sh "echo 'shell scripts to run static tests...'"
                  }
        }   


        stage ('Deployment Stage') {
            steps {
            sh "echo 'shell scripts to deploy to server...'"
        }
        }
    }
}
