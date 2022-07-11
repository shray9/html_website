pipeline { 
    agent any 
    
    stages {
        stage('Uploading to S3') { 
            steps { 
                sh 'aws s3 cp . s3://jinmeister-demo-app-2021 --recursive --acl public-read' 
            }
        }
    }
}
