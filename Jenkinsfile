pipeline {
  agent any

  triggers {
    githubPush()
  }

  stages {
    stage('Run Shell Script') {
      steps {
        sh './run.sh'
      }
    }
  }
}
