
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
                bat '"C:\\Windows\\System32\\cmd.exe" /c mvn clean install'
            }
        }
        stage('Test') {
            steps {
                bat '"C:\\Windows\\System32\\cmd.exe" /c mvn test'
            }
        }
    }
}
