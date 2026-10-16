pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo "Branch: ${env.BRANCH_NAME}"
        sh 'ls -la'
        sh 'git log -1 --oneline'
      }
    }
    stage('PR info') {
      steps {
        echo "BRANCH_NAME=${env.BRANCH_NAME}"
        echo "CHANGE_TARGET=${env.CHANGE_TARGET}"
        echo "CHANGE_ID=${env.CHANGE_ID}"
        sh 'exit 1'
      }
    }
  }
}
