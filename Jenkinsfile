pipeline {
  agent any
  stages {
    stage('Shell script 0') {
      steps {
	git credentialsId: 'gitty',
        url: 'https://github.com/capebhuma/test.git',
	branch: 'main'        
      }
    }
  }
}
