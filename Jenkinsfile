
pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Java code checkout completed'
            }
        }

        stage('Build Java') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run Java') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
