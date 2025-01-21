pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/username/repository.git' // Replace with your repo URL
            }
        }
        stage('Compile') {
            steps {
                sh 'gcc -o program program.c'
            }
        }
        stage('Run') {
            steps {
                sh './program'
            }
        }
    }
}

