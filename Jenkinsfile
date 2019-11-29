pipeline {
    agent { docker { image 'maven:3.6.0-jdk-12' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
