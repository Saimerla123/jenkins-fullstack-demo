pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Pulling code from GitHub...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                bat 'echo Building project'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Running tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                bat 'echo Deploy successful'
            }
        }
    }
}
