pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building HelloWorld Java Program'
                sh 'javac HelloWorld.java'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing HelloWorld Java Program'
                sh 'java HelloWorld'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying HelloWorld Java Program'
                echo 'HelloWorld Application Deployed Successfully'
            }
        }
    }
}

