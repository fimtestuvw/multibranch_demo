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
	stage('Feature1'){
	    steps {
	        echo 'Feature1'
		    sh 'ls -alt'
	    }
	}
    }
}
