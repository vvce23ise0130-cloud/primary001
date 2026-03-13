pieline {
  agent any

  stages {
    stage('compile java program')
      steps  {
        bat 'javac Helloworld.java'
      }
  }
}
stage('Run java program')  {
  steps {
    bat 'java Helloworld'
  }
}
}
