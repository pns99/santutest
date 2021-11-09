pipeline {
  agent any
  stages {
    stage ("Build master") {
      when {
        branch 'master'
      }
      steps {
        echo "Buiding master"
      }
    }
    stage ("Build Dev") {
      when {
        branch 'dev'
      }
      steps {
        echo "Buliding dev"
      }
    }
  }
}
