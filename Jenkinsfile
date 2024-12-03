pipeline{
    agent any
    stages{
        stage("make a directory"){
            steps{
                sh "mkdir ~/jenkins-test || true"
            }
        } 
        stage("make files"){
            steps{
                sh "touch ~/jenkins-test/file1.txt"
            }
        }
    }
}
