pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'docker build -t hello .'
                sh 'docker run hello'

            }
        }
    }
}
