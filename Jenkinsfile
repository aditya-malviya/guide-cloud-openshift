pipeline {
  agent any
   stages {
      stage ('Test') {
        steps {
          sh label: '', 
           script: 
           '''
           oc version
           '''
         } 
      }
   }
}
