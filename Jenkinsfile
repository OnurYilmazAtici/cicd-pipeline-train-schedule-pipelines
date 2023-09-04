pipeline {
agent any
  stages ('Build') {
  steps {
      echo ' Gradle build başlıyor baboş '
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'   
  }  
}

}
