pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning Repository'
            }
        }

        stage('Run Tests') {
            steps {
                bat 'pytest -v'
            }
        }
    }
}