pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "aws cloudformation create-stack --stack-name pancake --template-body file://myfile.yml --region us-east-1"
      }

    }

  }

}
