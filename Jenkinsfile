pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Getting source code from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building HTML Application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing HTML Application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application Deployed Successfully'
            }
        }
    }

    post {
        success {
            echo 'CI/CD Pipeline Successful!'
        }
    }
}