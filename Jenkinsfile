pipeline {
    agent any
    tools {nodejs "NodeJS"}
    stages {
        stage('Build') {
            steps {
                sh 'echo "hello world"'
            }
        }
        stage('Test') {
            steps {
                sh 'npm run test'
            }
        }
    }
}