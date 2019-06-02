pipeline {
    agent any;
    stages {
        stage ('Set Up'){
            steps {
                cleanWs();
                sh 'echo setting up my workspace'
            }
        }
        stage ('Checkout SCm'){
            steps {
                checkout SCM
            }
        }
        stage ('Compile Code'){
            steps {
                sh 'chmod +x app.sh'
            }
        }
        stage ('Development'){
            steps {
                sh 'chmod +x app.sh'
            }
        }
    }
}