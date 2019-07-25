pipeline {
    agent any 
    stages {
        stage('Checkout-Code') { 
            steps {
                //git credentialsId: '2bfadb15-f749-4b67-941d-32f23911e0e0', url: 'https://github.com/spoudel2/Jenkins_1.git'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo testing'
            }
        }
        stage('Deploy') { 
            steps {
               sh 'echo Deploy'
            }
        }
    }
}
