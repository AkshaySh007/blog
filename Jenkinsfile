pipeline {
  agent any
  stages {
    stage('pre-build') {
      steps {
        echo 'starting to build the application'
      }
    }

    stage('build') {
      steps {
        echo 'build'
        git(url: 'git@github.com:AkshaySh007/blog.git', branch: 'main')
      }
    }

  }
}