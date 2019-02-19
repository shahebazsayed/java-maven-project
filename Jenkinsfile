pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/shahebazsayed/java-maven-project.git', branch: 'master')
      }
    }
  }
}