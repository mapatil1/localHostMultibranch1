pipeline {
    agent any

    ### General project setup
    general:
      productiveBranch: 'master'


    stages {
        stage('Build') {
            steps {
                echo 'Building my app..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing my app..'
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying my app....'
            }
        }
    }
}
