pipeline {
    agent any 
    stages {
        stage('DELETION') { 
            steps {
                echo '--REMOVING REPOSITORY IF ALREADY EXIST --'
                sh "sudo rm -rf tobedeleted"
            }
        }
       stage('CLONE') { 
            steps {
                echo '--CLONE STAGE EXECUTION ---'
    sh "https://github.com/krutikmaru/tobedeleted.git"
            }
        }
        stage('TEST1') { 
            steps {
                echo '--TEST1 STAGE EXECUTION --'
            }
        }
        stage('TEST2') { 
            steps {
                echo '--TEST2 STAGE EXECUTION --'
            }
        }
        stage('BUILD') { 
            steps {
    echo '--BUILD STAGE EXECUTION --'
    sh "node JavaScript/add.js"
            }
        }
  stage('DEPLOY') { 
            steps {
    echo '--WILL SEE IN NEXT PART --'
            }
        }
    }
}