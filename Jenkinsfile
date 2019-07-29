pipeline {
  agent { label 'jenkins-slave' }
  parameters{
      string(defaultValue: "newbranch",
             description: 'Enter user role:', name: 'userRole')
             }
  stages {
      stage('listVals') {
          steps {
            echo "User's role = ${params.userRole}"
          }
      }
   }
 }
