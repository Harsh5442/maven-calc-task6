pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Harsh5442/maven-calc-task6.git'
            }
        }
        stage('Clean') {
            steps {
                sh 'mvn clean'
            }
        }
        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
