pipeline{
  agent{
    node{
      label "Slave-1"
      customeWorkspace "/home/jenkins/demo"
    }
  }
  stages{
    stage("Echo"){
      steps{
        sh 'echo HelloWorld'
      }
    }
  }
}
