pipeline {
    agent {
        any {
            image 'maven:3.8.1-adoptopenjdk-11' 
            args '-v /root/.m2:/root/.m2' 
        }
    }
    stages {
        stage('Build') { 
            steps {
<<<<<<< HEAD
                sh 'mvn -X test' 
=======
                sh 'mvn install' 
>>>>>>> 354e8d7a54a09116bf2017151ebba4c0f5e0526d
            }
        }
    }
}
