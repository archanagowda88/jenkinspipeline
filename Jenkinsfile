pipeline {
     agent any
     stages {
        stage("Pull Code"){
              steps {
                    echo "Pulling code from Github Repo..."
                 }
              }
          stage("Build") {
              steps {
                    echo "Building Package from Code..."
                 }
              }
          stage("Test") {
                steps {
                    echo "Testing Packaged..."
                 }
              }
          stage("Deploy") {
                steps {
                    echo "Deploying Application..."
                    }
              }
        }
    }
