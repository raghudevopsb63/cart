@Library('roboshop-shared-library@main') _

pipeline {
  agent any

  stages {

    // For Each Commit
    stage('Lint Checks') {
      steps {
        nodejs.lintChecks()
      }
    }

  } // End of Stages

}

