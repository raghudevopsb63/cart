pipeline {
  agent any

  stages {

    // For Each Commit
    stage('Lint Checks') {
      steps {
        sh '''
          ~/node_modules/jslint/bin/jslint.js server.js
        '''
      }
    }

  } // End of Stages

}

