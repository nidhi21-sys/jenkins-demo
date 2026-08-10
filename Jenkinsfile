pipeline {

    agent any

    stages {

        stage('Checkout') {

            steps {
                git branch: 'main', url: 'https://github.com/nidhi21-sys/jenkins-demo.git', credentialsId: 'github-token'
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
