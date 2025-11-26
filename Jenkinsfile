pipeline {
    agent any

    tools {
        jdk   'JDFK25'   
        maven 'Maven3'   
    }

    stages {
        stage('Build') {
            steps {
                sh 'java -version'
                sh 'mvn -version'
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
