pipeline {
  agent any
  stages {
    stage('Environment Config') {
      steps {
        echo 'Started Environment Config'
        sh '. ./setantenv.sh'
        sh 'echo $ANT_HOME'
      }
    }
  }
}