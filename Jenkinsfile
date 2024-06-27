pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Ajoute tes étapes de build ici
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Ajoute tes étapes de test ici
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Ajoute tes étapes de déploiement ici
            }
        }
    }
    post {
        always {
            echo "Pipeline finished Greeting datascientest"
            sh "./datascientest-clean.sh"
        }
    }
}