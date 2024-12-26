pipeline{
  agent any
  stages{
    stage('Built'){
      steps{
        echo "I am Building"
      }
    }
    stage('test'){
      steps{
        echo "I am testing"
      }
    }
    stage('Deploy'){
      steps{
        echo "I am Deploying"
      }
    }
  }
  post{
    success{
      echo "Your pipeline is success"
    }
    failure{
      echo "Pipeline failed"
    }
  }
}
