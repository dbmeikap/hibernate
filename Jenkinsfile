pipeline {
	agent {
        label {
            label ""
            customWorkspace "D:/work/codebase"
        }
    }
    stages {
        stage("foo") {
            steps {
                echo "Workspace dir is ${pwd()}"
            }
        }
    }
}