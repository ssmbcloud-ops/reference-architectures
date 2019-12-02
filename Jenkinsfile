pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        build(wait: true, quietPeriod: 2, job: 'test')
      }
    }

  }
}