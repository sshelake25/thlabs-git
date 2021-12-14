// Declarative //
pipeline {
  agent any 
  stages {
    stage('Hello World') { 
        steps { 
             echo 'Helloo Jenkins'
        }
    }

     stage('Good Byee') { 
        steps { 
             echo 'Byee Byee Jenkins'
        }
    }

    stage ('build zip file') {
      steps {
        archive *
      }
    }

  }
}
 