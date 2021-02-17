pipeline {
    agent any
    environment { 
        CC = "clanguage"
    }
    stages {
        stage('Example') {
            environment { 
                AN_ACCESS_KEY = credentials('my-predefined-secret-text') 
            }
            steps {
                sh "${CC}"
            }
        }
    }
}
