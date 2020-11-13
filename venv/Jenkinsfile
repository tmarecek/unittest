pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'C:/Users/marecekt/PycharmProjects/unittest/venv/Scripts/python.exe C:/Users/marecekt/PycharmProjects/unittest/main.py'
      }
    }
    stage('test') {
      steps {
        bat 'C:/Users/marecekt/PycharmProjects/unittest/venv/Scripts/python.exe C:/Users/marecekt/PycharmProjects/unittest/basic_test.py'
      }
    }
}
}