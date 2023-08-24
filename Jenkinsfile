pipeline {
    agent {
        docker { image 'docker.io/python:3.10-slim' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'pip install pipx'
		sh 'pipx run nbconvert lucia.ipynb'
            }
        }
    }
}
