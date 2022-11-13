pipeline{
  agent any
  stages{
    stage('One'){
      steps{
        echo "Hi Sudheesh"
      }
      stage('Two'){
        sh '''#!/bin/bash
            uptime
           '''
      }
        stage('Three'){
          echo "This is the third stage"
        }
      stage('Four'){
          echo "This is the Fourth stage"
        }
      stage('Fifth'){
          echo "This is the Fifth stage"
        }
    }
  }
}
  
