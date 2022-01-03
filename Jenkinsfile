pipeline {
  stages {
    stage('Build') {
      steps {
        sh './gradlew build'
        archiveArtifacts(artifacts: 'dist/trainSchedule.zip')
      }
    }
  }
}
