pipeline {
  agent any
  stages {
    stage('stage01') {
      parallel {
        stage('stage01') {
          steps {
            sh 'echo hello worldo >> findme14h.txt'
            echo 'good by crewl world'
          }
        }

        stage('') {
          steps {
            ws(dir: '/var/tmp')
          }
        }

      }
    }

  }
}