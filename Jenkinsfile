pipeline {
  agent any
  stages {
    stage('build'){
      steps {
        echo "Build Automation"
        sh './gradlew --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip' 
      }
    }
  }
}
