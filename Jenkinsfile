pipeline {
        agent any
        stages {
            stage('Hello') {
                steps {
                    echo "Branch: ${env.BRANCH_NAME}"
                    sh 'git log -1 --oneline'
                    sh 'ls -la'
                }
        }
            }
    }
