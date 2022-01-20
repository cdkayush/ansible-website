pipeline {
    agent any
    stages {
        stage('deploy the webserver') {
            steps {
                sh 'ansible-playbook ./playbook.yml'
            }
        }
    }
}

