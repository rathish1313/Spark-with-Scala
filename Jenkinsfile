pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'Mongo_fullload', wait: true)
      }
    }

    stage('deploy') {
      steps {
        echo 'second stage'
      }
    }

  }
}