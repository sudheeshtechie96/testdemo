pipeline{
  agent any
  stages{
    stage('One'){
      steps {
        echo 'This is the stage one'
      }
    }
    stage('Two'){
      steps {
        sh '''#!/bin/bash
              uptime
              '''
      }
   }
    stage('Three'){
      steps {
        sh '''#!/bin/bash
              sudo apt install docker.io -y
              '''
      }
      }
    }
    stage('Four'){
      steps {
        echo 'This is the stage fourth'
      }
    }
    stage('Fifth'){
      steps {
        echo 'This is the stage fifth'
      }
    }
    stage('Sixth'){
      steps {
        echo 'This is the stage sixth'
      }
    }
  }
}
  
