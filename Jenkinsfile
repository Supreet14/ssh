pipeline {
    agent any
    stages {
        stage('Example stage 1') {
            steps {
                withCredentials(bindings: [sshUserPrivateKey(credentialsId: '44.211.198.19', \
                                                             keyFileVariable: 'SSH_KEY_FOR_ABC')]) {
                                                                sh 'ssh -t ${SSH_KEY_FOR_ABC} ec2-user@3.82.212.252'
                                                                sh 'chmod 700 ${SSH_KEY_FOR_ABC}'
                                                                sh 'ssh -tt ${SSH_KEY_FOR_ABC} ec2-user@3.82.212.252'
                                                                sh 'pwd'
        
}
                }
                
                  
            }
            }
        }
