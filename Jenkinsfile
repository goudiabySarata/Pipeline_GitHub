pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Récupérer le code source depuis le dépôt Git
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Compilation du code Java
                bat 'javac Main.java'
            }
        }
        stage('Test') {
            steps {
                // Exécution du code Java
                bat 'java Main'
            }
        }
        stage('Deploy') {
            steps {
                // Déployer le code sur le serveur de production
                echo "Déploiement sur le serveur de production en cours"
            }
        }
    }
}
