pipeline {
  stages {
    stage('Application build') {
      steps {
        echo "building application"
        sh("""chmod 755 hello_world.sh
              sh hello_world.sh""")
      }
    }
    
    stage('Quality scan') {
       steps {
          echo "scanning..."
       }
    }
    
    stage('Deploy to AWS') {
      steps {
         echo "deploying ..."
      }
    }
  }
}
