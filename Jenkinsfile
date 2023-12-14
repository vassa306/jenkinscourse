pipeline {
    agent any
    stages {
        stage('Build') {
            when {
               changeRequest()
            }

            steps {
                echo 'Running because change request exists'
            }
        }
    }
}
