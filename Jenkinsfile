pipeline {
  agent {
    node {
      label "docker-agent-alpine"
    }
  }
  triggers {
    pollscm '*/5 * * * *'
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
