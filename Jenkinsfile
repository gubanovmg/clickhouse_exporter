pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'cd ..'
      }
    }

    stage('release') {
      steps {
        archiveArtifacts '12323'
        acceptGitLabMR()
      }
    }

  }
}