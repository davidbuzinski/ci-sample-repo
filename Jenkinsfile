pipeline {
  agent any
  stages {
    stage('Run MATLAB Tests') {
      steps {
        runMATLABCommand(
          command: 'addpath("code");runtests("tests")'
        )
        // runMATLABTests(
        //   sourceFolder: ['code']
        // )
        // runMATLABBuild()
      }
    }
  }
}
