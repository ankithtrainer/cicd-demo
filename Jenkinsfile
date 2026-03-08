pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/ankithtrainer/cicd-demo.git'
            }
        }
        stage('Build') {
            steps {
                echo "Building application..."
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
        stage('Deploy') {
            steps {
                bat 'mkdir C:\\deploy-demo'
                bat 'copy index.html C:\\deploy-demo'
            }
        }
    }
}