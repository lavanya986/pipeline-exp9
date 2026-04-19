pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac Calculator.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Calculator'
            }
        }
    }
}
