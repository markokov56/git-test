pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('build') {
            steps {
                echo 'php --version'
            }
        }
    }
}
