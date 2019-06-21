pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    ssh ec2-user@52.66.250.78
                    aws s3 ls
                '''
            }
        }
    }
}
