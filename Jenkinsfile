pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Pavanclg/javapipeline.git'
            }
        }

        stage('Build') {
            steps {
                sh 'javac Code.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Code'
            }
        }
    }
}
