pipeline{
  agent any
  stages{
    stage('One'){
      steps{
        echo "Hi Sudheesh"
      }
      stage('Two'){
        steps{
        sh '''#!/bin/bash
            uptime
           '''
        }
      }
        stage('Three'){
          steps{
          echo "This is the third stage"
          }
        }
      stage('Four'){
        steps{
          echo "This is the Fourth stage"
        }
        }
      stage('Fifth'){
        steps{
          echo "This is the Fifth stage"
        }
        }
    }
  }
}
  
