pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/adn1107/docker-apache-perl', branch: 'master')
      }
    }
  }
}