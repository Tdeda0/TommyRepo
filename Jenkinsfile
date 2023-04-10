pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
        sh'aws cloudformation create-stack --stack-name Pancake --template-body file://myFile.yml --region us-east-1'
      }
    
    }
  
  }

}
