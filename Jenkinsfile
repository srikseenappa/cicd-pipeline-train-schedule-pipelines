pipeline{
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation-Srikanth Seenappa'
        sh './gradlew build'
        archiveArtifacts artifacts:'dist/trainSchedule.zip'
      }
    }
  }
}
