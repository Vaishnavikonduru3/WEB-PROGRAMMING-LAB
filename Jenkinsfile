pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''Set VS_SIGN=yes
Set VS_OUTLOOK_UI_FEATURE=yes
Set VS_VERSION_MAJOR=7
Set VS_VERSION_MINOR=7
Set VS_VERSION_BUILD=0
Set BUILD_NUMBER=1
build.bat Release en-US
'''
      }
    }

  }
}