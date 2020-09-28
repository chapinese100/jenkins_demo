pipeline {
    agent any
    tools {
        maven 'LocalMaven'
        jdk   'LocalJDK'
    }
    stages {
        stage('build') {
            steps {
                echo "Ivan is becoming a DevOps Engineer...!!!!"
                sh 'mvn compile'
        }
    }
        stage('package') {
            steps {
                echo "Ivan is becoming a DevOps Engineer Senior CI/CD...!!!!"
                sh 'mvn test'
           }
       }
   }
}
