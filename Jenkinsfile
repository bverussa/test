pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        echo "Executing Ansible Playbook"
        sh 'ssh bruno@10.211.55.4 "cd /home/bruno/workspace/test && ansible-playbook playbook_deploy.yml"'
      }
    }
  }
}
