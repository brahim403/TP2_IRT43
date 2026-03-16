pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/brahim403/TP2_IRT43.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
