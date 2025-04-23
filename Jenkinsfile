pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Ajoutez vos commandes de build ici
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Ajoutez vos commandes de test ici
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Ajoutez vos commandes de déploiement ici
            }
        }
    }
    post {
        always {
            echo 'This will always run.'
        }
        success {
            echo 'This will run only if the pipeline succeeds.'
        }
        failure {
            echo 'This will run only if the pipeline fails.'
        }
    }
}