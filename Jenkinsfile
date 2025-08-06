pipeline {
  agent any
  stages {
    stage('Run MATLAB Tests') {
      steps {
        runMATLABCommand(
          command: 'runtests'
        )
        // runMATLABTests(
        //   sourceFolder: ['code']
        // )
        // runMATLABBuild()
      }
    }
  }
}
