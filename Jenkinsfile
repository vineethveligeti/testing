pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Hello World'
                echo env.CHANGE_ID
                echo env.GIT_BRANCH
                echo env.BRANCH_NAME
            }
        }
        stage('Test') { 
            steps {
                echo 'Hello World2'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Hello World3' 
            }
        }
    }
}
