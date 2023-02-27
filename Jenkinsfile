pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh 'ech "thi is my second step"'
                sh '''
                echo "Multiline shell steps works too"
                    ls -lah
                '''
            }

        }
    }
}