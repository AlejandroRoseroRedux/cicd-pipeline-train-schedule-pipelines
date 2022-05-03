pipeline{
  agent any
  stages{
    stage ('Build'){
      steps{
        echo 'running build automation - ALEJO RULES'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
