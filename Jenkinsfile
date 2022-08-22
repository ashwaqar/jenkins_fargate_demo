pipeline {
  agent { label 'ecsAgent'}
  stages {
    stage('Running Build') {
      steps {
        echo 'Successfully build the docker image and running this command inside it!'
        echo "${params.Environment}"
        echo "${params.Host}"
      }
    }
  }
}
