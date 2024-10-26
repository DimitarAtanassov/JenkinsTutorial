/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.13.0-alpine3.20' } }
    environment {
        MSYS_NO_PATHCONV = '1'
    }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}

