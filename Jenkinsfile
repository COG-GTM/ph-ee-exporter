pipeline {
    agent any
    tools {
        jdk 'jdk-21'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'mvn -U clean package deploy'
            }
        }
    }
}
