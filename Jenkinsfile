pipeline{
 agent any
 stages{
    stage 'build'{
      steps{
        echo ' running jenkins pipeline project'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
   }
   
}
