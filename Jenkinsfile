pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/ganeshgond07/cicd-demo'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}