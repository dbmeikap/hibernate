pipeline {
    agent any 
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
            }
        }
        stage('Example Test') {
            steps {
                echo 'Hello, JDK'
            }
        }
    }
	post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}