pipeline { 
  agent any 
  stages { 
    stage ('Build') { 
      steps { 
      echo ' Running Build automation by Kawaljit ' 
      sh './gradlew build --no-daemon '
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    } 
  }
}
