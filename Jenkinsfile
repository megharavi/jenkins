pipeline {
    agent any
    environment { 
        CC = "clanguage"
    }
    stages {
        stage('Example') {
            environment { 
                AN_ACCESS_KEY = "${CC}" 
            }
            steps {
                echo "${CC} + 2"
            }
        }
    }
}
