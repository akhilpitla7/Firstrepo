pipeline {
  agent any
  stages {
  /*"Build" and "Test" stages omitted */
  stage('Deploy-Dev') {
    steps {
      echo "Hello"
    }
  }
  stage('Deploy-QA') {
    steps {
      echo "QA"
      input "Does the staging environment looks OK?"
    }
  }
  stage('Deploy-Production') {
    steps {
      echo "Production"
    }
  }
}
}
