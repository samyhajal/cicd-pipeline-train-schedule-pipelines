pipeline {
  stages {
    stage('Build') {
      steps {
        echo 'Building Gradle'
        sh './gradlew build'
        archiveArtifacts(artifacts: 'dist/trainSchedule.zip')
      }
    }
  }
}
