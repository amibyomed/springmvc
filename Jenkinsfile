pipeline {
agent any
stages{
  stage('Build'){
    steps{
   bat " $ { mvnHome } \\ bin \\ mvn clean install"
    }
  }
  stage('Test'){
    steps{
   bat " $ { mvnHome } \\ bin \\ mvn test"
    }
  }
}
}
