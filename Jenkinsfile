pipeline{
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation-Srikanth Seenappa'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts:'dist/trainSchedule.zip'
      }
    }
  }
}
