pipeline {
     agent any
    stages {
        stage('clone repo') {
            steps {
                sh 'echo "clone repo"'
            }
        }
        stage('run test') {
            steps {
                sh 'echo "run test "'
            }
        }
        stage(' Build artifact  ') {
            steps {
                sh 'echo "build artifact"'
            }
        }
        
    }
}
 

~##hello
