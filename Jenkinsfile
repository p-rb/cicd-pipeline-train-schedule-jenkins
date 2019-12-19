pipeline {
  agent any
  stages {
    stage ('Build')
      {
      steps {
      echo 'Running this build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
      }
   }
}
