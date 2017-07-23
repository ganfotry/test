pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
		 stage('check1') {
            steps {
                sh 'cal'
            }
        }
        stage('check2') {
            steps {
                sh 'date'
            }
        }
    }
}