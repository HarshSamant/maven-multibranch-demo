pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('demo-app') {
                    sh 'mvn clean package'
                }
            }
        }
    }
}

