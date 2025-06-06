pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/7navya8/Maven.git'
            }
        }

        stage('Build') {
            steps {
                script {
                    sh 'mvn clean install'
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    sh 'mvn test'
                }
            }
        }
    }
}
