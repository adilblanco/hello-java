pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#Build Steps:
echo "Compiling ... "
javac HelloWorld.java
echo "Execution ..."
java HelloWorld
jar cvfe HelloWorld.jar HelloWorld *.class
echo "============================"'''
      }
    }

  }
}