pipeline {
  agent any
  stages {
    stage('build'){
      echo "Build Automation"
      sh './gradlew --no-daemon'
      archiveArtifacts artifatcs: 'dist/trainSchedule.zip'
    }
  }
}
