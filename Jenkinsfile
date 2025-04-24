pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/kimwk0229/testetwet.git'
                sh "mvn clean package"
            }

        }
    }
}
