pipeline{
  agent{
    node{
      label "Slave-1"
      customWorkspace "/home/jenkins/demo"
    }
  }
  stages{
    stage("Echo"){
      steps{
        sh 'echo HelloWorldTest'
      }
    }
  }
}
