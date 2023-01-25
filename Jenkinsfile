pipeline {
    agent  any
    stages {
        stage('Init') { 
            steps {
                echo 'Stage Init!' 
            }
        }
        stage('Build') {
            steps {
                echo 'Stage Build!'
                sh 'npm install'
            }
        }  
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}
