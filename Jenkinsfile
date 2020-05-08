pipeline {
   agent any
   stages {
      stage('Hello') {
         steps {
            sh 'ssh 192.168.2.128'
            sh 'python main.py'
         }
      }
   }
}