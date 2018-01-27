pipeline {
	agent any
	tools { 
        maven 'Maven2' 
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}