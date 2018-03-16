pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd /Users/pullarao/ninja/workspace/backend/asgard

mvn install

echo "Build Success"'''
      }
    }
  }
}