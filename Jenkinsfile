pipeline {
  agent any
  stages {
      stage('Build') {
         echo 'Running Build automation'
         sh './gradlew build --no-daemon'
         archiveArtifacts artifacts: 'dist/trainSchedule.zip'
   } 
  }
}
