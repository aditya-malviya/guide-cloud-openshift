pipeline {
  agent any
   stages {
      stage ('Test') {
        steps {
          sh label: '', 
           script: 
           '''
           oc version
           oc login --token=T0ujqgDvlARrDVcH48s9fp57XBraKTfE6pTG2q_zK0s --server=https://api.ca-central-1.starter.openshift-online.com:6443
           oc new-project Hello-Jenkins
           '''
         } 
      }
   }
}
