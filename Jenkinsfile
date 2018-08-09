
pipeline {

    agent any
    tools {
        maven 'maven.3.5.4' 
    }
    stages {
        stage('Compile stage') {
            steps {
                bat "mvn compile" 
        }
    }

         stage('testing stage') {
             steps {
                bat "mvn test"
        }
    }

          stage('deployment stage') {
              steps {
                bat "mvn deploy"
        }
    }

  }

}

       