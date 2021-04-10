pipeline {
    agent {
        label 'jenkins2_vm_agent'
    }

    stages {
        stage('Main') {
            steps {
                echo 'Main Stage'
                pwd()
                sh 'ls -alt'
            }
        }
    }
}
