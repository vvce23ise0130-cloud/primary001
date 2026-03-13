pieline {
  agent any

  stages {
    stage('compile java program')
      steps  {
        bat 'javac HelloWorld.java'
      }
  }
}
stage('Run java program')  {
  steps {
    bat 'java HelloWorld'
  }
}
}
