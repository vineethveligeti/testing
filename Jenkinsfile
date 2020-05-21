pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Hello World'
                echo "CHANGE_ID : " env.CHANGE_ID
                echo "GIT_BRANCH : " env.GIT_BRANCH
                echo "BRANCH_NAME : " env.BRANCH_NAME
                echo "GIT_URL : " env.GIT_URL
                echo "GIT_COMMIT : " env.GIT_COMMIT
                echo "GIT_REVISION : " env.GIT_REVISION
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
