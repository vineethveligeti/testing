pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Hello World'
                echo "GIT_BRANCH : $GIT_BRANCH" 
                echo "BRANCH_NAME : $BRANCH_NAME" 
                echo "GIT_URL : $GIT_URL" 
                echo "GIT_COMMIT : $GIT_COMMIT"
                bat "pylint **/*.py"
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
