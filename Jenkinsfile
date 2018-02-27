pipeline {
    agent none
    stages {
        stage('Build') {
            agent any  
            steps {
                sh 'packer build packer.json' 
            }
        }
    }
}
