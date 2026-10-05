
pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat 'docker build -t my-kube1:latest .'
            }
        }
    }
}