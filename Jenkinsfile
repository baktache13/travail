pipeline {
    agent any
    stages {
        stage('Récupération du code source') {
            steps {
                // Récupération du code depuis Git
                git 'https://github.com/baktache13/travail.git'
            }
        }
        stage('Affichage de la date système') {
            steps {
                // Affichage de la date système
                sh 'date'
            }
        }
    }
}