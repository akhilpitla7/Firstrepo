pipeline {
  agent any
  /*"Build" and "Test" stages omitted */
  stages ('Deploy-Dev') {
    steps {
      echo "Hello"
    }
  }
  stage ('Deploy-QA') {
    steps {
      echo "QA"
      input "Does the staging environment looks OK?"
    }
  }
  sstage ('Deploy-Production') {
    steps {
      echo "Production"
    }
  }
}
