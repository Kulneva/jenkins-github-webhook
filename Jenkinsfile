pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build Backend') {
            steps {
                echo 'This satge will build the code.'
            }
        }
        stage('Build Frontend') {
            steps {
                sh 'javac Hello.java'
                sh 'java Hello'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Will Deply the code.'
            }
        }
        stage('Test') {
            steps {
                echo 'Tests will be executed in this stage'
            }
        }
        stage('Release') {
            steps {
                echo 'Release is done successfully'
            }
        }
    }
}
