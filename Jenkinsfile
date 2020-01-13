pipeline {
  agent any
  
  stages {
  
    stage ('Build') {
      steps {
        step {
          echo 'Running build automation'
          sh './gradlew build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
        
        
      }
        
    }
  
  
  
  }

}
