pipeline {
    agent{
        label "linux"
    }
    stages{
        stage("state directory"){
            steps{
                sh "ls -la"
                sh "pwd"
            }
        }
        stage("check version"){
            steps{
                sh "ansible-playbook --version"
            }
        }
    }
}