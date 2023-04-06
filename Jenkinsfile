pipeline {
  agent any
  stages {
    stage(build){
      sh'aws cloudformation create-stack --template-body file://myFile.yml --stack-name Pancake --region us-east-1'
    
    }
  
  }

}
