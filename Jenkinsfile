pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'echo Build complete!'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'echo Tests Passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'echo Deployment successful!'
            }
        }
    }
}

