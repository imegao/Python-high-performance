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
                sh 'python main.go'
            }
        }
    }
}