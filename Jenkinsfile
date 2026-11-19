pipeline{
  agent any
  stages{
    stage("Clean and install"){
      steps{
        bat "mvn clean install"
    }
    stage("Test"){
      steps{
        bat "mvn test"
    }
    stage("Package"){
      steps{
        bat "mvn package"
    }
}
