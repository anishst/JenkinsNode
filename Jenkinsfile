pipeline {
    agent {
        dockerfile true
    }

    stages {
        stage('Build') {
            steps {
                sh 'node --version'
                echo 'Getting working dir...'
                sh 'pwd'
            }
        }
    }
}
