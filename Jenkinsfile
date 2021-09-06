pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world of war Raghu bhai..!!!' 
		dir('/var/lib/jenkins/workspace/example-pipeline'){
		git 'https://github.com/gogateman/mg-mvn.git'
		}
            }
        }
    }
}
