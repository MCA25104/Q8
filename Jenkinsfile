pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/MCA25104/job4_code.git'
            }
        }
        stage('Build') {
            steps {
                bat 'javac code.java'
            }
        }
        stage('Execute') {
            steps {
                bat 'java code'
            }
        }
    }
}
