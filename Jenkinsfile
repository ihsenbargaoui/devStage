pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'make build'  // Remplace cette commande par celle nécessaire pour ton projet
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'make test'   // Remplace cette commande par celle nécessaire pour tes tests
            }
        }
    }
}
