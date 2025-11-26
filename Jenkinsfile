pipeline {
    agent any

    tools {
        maven 'Maven3'   // must match the Jenkins UI name
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
