pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'minimal pipeline.'
      }
    }

    stage('git') {
      steps {
        git(url: 'https://github.com/Tamilvanan-devops/Lampstack-Ansible-Playbook', branch: 'master', credentialsId: 'furioustamil@8')
      }
    }

  }
}