pipeline {
  agent any
  stages {
    stage('pull') {
      agent any
      steps {
        git(url: 'https://github.com/marcpubandre/qualimetry.git', branch: 'master')
      }
    }
    stage('push') {
      agent any
      steps {
        git(url: 'https://github.com/marcpubandre/qualimetry.git', branch: 'master')
      }
    }
  }
}