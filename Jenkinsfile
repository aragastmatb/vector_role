pipeline {
    agent{
        label "linux"
    }
    stages{
        stage("state directory"){
            steps{
                sh "ls -la"
            }
        }
        stage("check version"){
            steps{
                sh "ansible-playbook --version"
            }
        }
    }
}