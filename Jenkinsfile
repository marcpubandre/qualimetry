pipeline {
  agent any
  stages {
    stage('commit') {
      steps {
        git(url: 'https://github.com/marcpubandre/qualimetry.git', branch: 'master')
      }
    }
    stage('pull') {
      steps {
        git(url: 'https://github.com/marcpubandre/qualimetry.git', branch: 'master')
      }
    }
    stage('push') {
      steps {
        git(url: 'https://github.com/marcpubandre/qualimetry.git', branch: 'master')
      }
    }
  }
}