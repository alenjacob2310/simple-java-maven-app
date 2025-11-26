pipeline {
    agent any

    tools {
        jdk   'JDK25'    // from JDK config
        maven 'Maven3'   // from Maven config
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
