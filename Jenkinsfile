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

        stage('understage1') {
          steps {
            input(message: 'my', id: 'dog', ok: 'has')
          }
        }

      }
    }

    stage('') {
      steps {
        waitUntil()
      }
    }

  }
}