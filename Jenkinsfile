pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('Build more') {
            steps {
                sh '''
                    echo "Multiline shell steps works too"
                    echo "Another line to check at 16:36 it is there a problem with time difference"
                    ls -lah
                '''
            }
        }
    }
}
