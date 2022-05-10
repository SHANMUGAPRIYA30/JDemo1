pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage'
                build 'BuildDemo'
            }
        }
        stage('Develop') {
            steps {
                echo 'Develop Stage'
                build 'DevelopDemo'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Stage'
                build 'TestDemo'
            }
        }
    }
}
