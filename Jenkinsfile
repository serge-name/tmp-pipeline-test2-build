pipeline {
  agent {
    docker { image 'debian:9' }
  }

  stages {
    stage('build') {
      steps {
        sh 'pwd'
        sh 'ls -l'
        sh 'ls -l ..'
/*
        sh 'apt-get update'
        sh 'apt-get install -y gnupg'
        sh 'apt-key add repo.key'
        sh 'echo "deb http://10.10.2.4:8331/misc/ stretch main" >>/etc/apt/sources.list'
        sh 'apt-get update'
        sh 'apt-get install -y aptly-simple'
        sh 'hostname -f'
        sh 'ip a sh'
        sh 'pwd'
        sh 'ls -la'
        sh 'date -R >ololo'
*/
      }
    }
  }

/*
  post {
    always {
      archive 'ololo'
    }
  }
*/
}
