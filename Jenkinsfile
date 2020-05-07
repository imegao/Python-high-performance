pipeline {
    agent none
    stages {
        stage('Build') {
        agent {
                docker {
                    image 'python'
                }
            }
            steps {
                sh 'python -m main.py'
                echo "is build"
            }
        }
        stage('Test') {
            steps {
                echo "is test"
            }
        }
        stage('Deploy') {
            steps {
                sh 'is deploy'
            }
        }
     }
}