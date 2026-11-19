pipeline{
  agent any
  stages{
    stage("Clean and install"){
      steps{
        bat "mvn clean install HMS"
    }
    stage("Test"){
      steps{
        bat "mvn test HMS"
    }
    stage("Package"){
      steps{
        bat "mvn package HMS"
    }
}
