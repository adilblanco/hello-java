pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#Build Steps:
echo "Compiling ... "
javac HelloWorld.java
'''
      }
    }

    stage('Compile') {
      steps {
        sh '''echo "Compiling ..."
javac HelloWorld.java
echo "============================"'''
      }
    }

    stage('Deploy') {
      steps {
        sh '''echo "Deploying ... "
java HelloWorld
echo "============================"'''
      }
    }

  }
}