pipeline {
    agent any

    stages {
        stage('first') {
            steps {
                sh 'molecule test -s centos_7'
            }
        }
    }
}
