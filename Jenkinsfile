pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh -c 'uname -a'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
