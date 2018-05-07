pipeline {
    agent { docker { image 'maven:3.7.0' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}