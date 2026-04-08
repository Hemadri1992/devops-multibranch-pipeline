pipeline {
    agent any // agent defines where to run
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'

           }
       }
	   stage('deploy') {
            steps {
                echo 'deploy...'

           }
       }

    post {
        always {
            echo 'Cleaning up...'
        }
    }
}

