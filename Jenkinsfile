pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "Building ... "
javac HelloWorld.java
'''
      }
    }

    stage('Compile') {
      steps {
        sh '''echo "Compiling ..."
javac HelloWorld.java
'''
      }
    }

    stage('Deploy') {
      steps {
        sh '''echo "Deploying ... "
java HelloWorld
'''
      }
    }

  }
}