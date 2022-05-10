pipeline {
  agent any

  stages {
    stage ("Hello") {
      steps {
        echo "Hello, World"
      }
    }

    stage ("Segundo stage") {
      steps {
        sh """
          hostname
          pwd
          ls -la
        """
      }
    }
  }
}
