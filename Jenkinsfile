pipeline {
    agent any

    stages {
        stage('Testing Environment') {
            steps {
		echo "no tests available"
                }
            }
        stage('Build') {
            steps {
		sh 'docker build -t="sam315/individual-project-frontend:latest" .'
                }
            }
        stage('Deploy') {
            steps {
		sh 'docker push sam315/individual-project-frontend:latest'
            }
        }
    }
}


