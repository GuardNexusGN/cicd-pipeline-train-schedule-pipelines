pipeline {
  agent any 
  stages {
    stage ('Build') {
      steps {
        echo 'Running build authomation'
        sh './gradlew build --no-daemon'
        archiveArifacts artifacts: 'dist/trainSchedule.zip'
      }
    } 
  }
}
