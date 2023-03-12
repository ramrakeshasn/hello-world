pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'Hello Suresh this is my first Jenkins job under your guidance'
        git(url: 'https://github.com/ramrakeshasn/hello-world.git', branch: 'master', changelog: true)
      }
    }

  }
}