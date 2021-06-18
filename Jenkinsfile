pipeline {
    
    agent any
    
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install react-scripts'
            }
        }
        stage('Test') {
            steps {
                sh 'npm Test'
            }
        }
        stage('Deliver') {
            steps {
                sh 'npm start'
            }
        }
    }
}
