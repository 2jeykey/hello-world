pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hi"'
                sh '''
                    echo "Multiline !~!"
                    ls -lah
                '''
            }
        }
    }
}
