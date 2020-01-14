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
               
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying my app....'
            }
        }
    }
}
