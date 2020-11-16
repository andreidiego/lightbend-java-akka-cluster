
pipeline {
    agent any
    stages {
        stage('build') {
            environment {
                HOME="."
            }
            steps {
                sh 'java --version'
                sh 'which java'
                sh 'mvn --version'
            }
        }
    }
}
