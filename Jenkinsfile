pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                    echo "Without docker"
                    ls -la
                    touch container-no.txt
                '''
            }
        }
        
        
    }
}
