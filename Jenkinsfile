pipeline {
  agent any
  stages {
    stage('git ') {
      steps {
        git(url: 'https://github.com/yogeshkr167', branch: 'main', changelog: true, poll: true)
      }
    }

  }
}
