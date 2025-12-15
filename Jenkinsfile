pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      agent any
      steps {
        git(url: 'https://github.com/kiltonmithun/python3_labs', branch: 'main', credentialsId: 'githubpat', poll: true, changelog: true)
      }
    }

  }
}