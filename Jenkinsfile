pipeline {
    agent any
    stages {
        stage('Salutation à tout le monde devops') {
            steps {
                echo 'Bonjour '
            }
        }
        stage('Début du pipeline ...') {
            steps {
                echo 'Chargement'
            }
        }
        stage('Création image Docker') {
            steps {
                sh 'docker build -t Bensalem_ams_2024 .'
            }
        }
    }
}
