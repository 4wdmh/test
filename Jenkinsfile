pipeline {
    //agent { docker { image 'python:3.5.1' } }
    agent any 
    //{ 
        //docker { 
        //    image 'kroniak/ssh-client'
        //    args '-u root:root'
            //args '-v /etc/passwd:/etc/passwd:ro'
        //} 
    //}
    environment {
        // The MY_KUBECONFIG environment variable will be assigned
        // the value of a temporary file.  For example:
        //   /home/user/.jenkins/workspace/cred_test@tmp/secretFiles/546a5cf3-9b56-4165-a0fd-19e2afe6b31f/kubeconfig.txt
        MHOLLAI_SSH_KEY = credentials('MHOLLAI_SSH_KEY')
    }

    stages {
        stage('build') {
            steps {
                //sh 'python --version'
                sh 'ls '
                sh 'pwd'
                sh 'ls /var/lib/jenkins/workspace/pipeline_main'
                //sh '/usr/bin/scp -i $MHOLLAI_SSH_KEY -o StrictHostKeyChecking=no Jenkinsfile mhollai@192.168.42.242:/home/mhollai'
            }
        }
    }
}
