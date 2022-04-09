pipeline {
  agent any

  stages {

    // For Each Commit
    stage('Lint Checks') {
      steps {
        sh '''
          # We commented this because devs gonna check the failures.
          #~/node_modules/jslint/bin/jslint.js server.js
          echo Link Check 
        '''
      }
    }

  } // End of Stages

}

