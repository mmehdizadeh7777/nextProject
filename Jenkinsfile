pipeline {
  agent {
    node {
      label "docker-agent-alpine"
    }
  }
  stages {
    stage("Build") {
      steps {
        echo "Building the application ..."
      }
    }
   stage("Test") {
      steps {
        echo "Testing the application ..."
      }
    }
   stage("Deploy") {
      steps {
        echo "Deploying the application ..."
      }
    }
  }
}
