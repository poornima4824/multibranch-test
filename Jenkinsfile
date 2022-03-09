pipeline {
 agent any
 parameters {
  string(name: 'user', defaultValue: 'poornima', description: 'A user that triggers the pipeline')
 }
 stages {
  stage('Trigger pipeline') {
   steps {
    echo "Pipeline triggered by  user: ${user}"
   }
  }
 }
}
