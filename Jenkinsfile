pipeline {

    agent any

    stages {

        stage('Checkout') {

            steps {
                git 'https://github.com/nidhi21-sys/jenkins-demo.git'
            }

        }

        stage('Build') {

            steps {
                echo 'Building Project...'
            }

        }

        stage('Test') {

            steps {
                echo 'Testing Project...'
            }

        }

    }

}
