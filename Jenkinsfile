pipeline {
  agent any
  stages {
    stage('initialize') {
      steps {
        bat(script: '../M88Type4_Portage/config_project_path.bat', returnStatus: true, returnStdout: true)
      }
    }
  }
}