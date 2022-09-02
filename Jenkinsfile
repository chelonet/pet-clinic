pipeline {
    agent any  
    stages {

      stage('HOLA MUNDO') {
        steps {
          script {
            sh 'set -x; chmod +x gradlew'
            sh('set +x; ./gradlew sonarqube -Dsonar.login=ffeb58259cd5e9d0e8ee08a6b95be1f0df90df76 -Dsonar.branch.name=feature-jenkins')
            }         
          }
        }
      }

    }
  
