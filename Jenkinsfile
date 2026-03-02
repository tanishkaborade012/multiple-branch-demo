pipeline {
  agent any
  stages{
    stage ('Build') {
      steps{
        echo "Building branch is : ${env.BRANCH_NAME}"
        echo "Feature 1 pipeline"
      }
    }
    stage ('Test') {
      steps{
        echo "Running tests on ${env.BRANCH_NAME}"
      }
    }
  }
}
