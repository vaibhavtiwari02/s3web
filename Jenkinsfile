pipeline{
  agent any
  stages {
    stage('build with version'){
      step{
        sh "java --version"
        sh "ls"
      }

    }
    stage('deploy'){
      steps {
        sh "aws s3 cp index.html s3://vaibhav1jenkins"
      }
    }
  }
}
