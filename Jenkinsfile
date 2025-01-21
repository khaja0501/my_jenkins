pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/khaja0501/my_jenkins.git' 
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

