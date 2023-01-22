pipeline {
    agent any
    stages {
        stage('Example stage 1') {
            steps {
                withCredentials([sshUserPrivateKey(credentialsId:'44.211.198.19',keyFileVariable:'key')]) {
                   sh 'ssh -t ${key} ec2-user@3.82.212.252'
                    sh 'chmod 400 ${key}'
                    sh 'ssh -tt ${key} ec2-user@3.82.212.252'
                    sh 'ssh -o StrictHostKeyChecking=no -l ec2-user 3.82.212.252 uname -a' 
                     sh 'pwd'
                    
        
}
                }
                
                  
            }
            }
        }
