pipeline{
agent any  
stages{
stage('checkout code'){
  steps{
    git 'https://github.com/Bhanu8978/jenkins/edit/master/Jenkinsfile'
  }}
  stage('build'){
    steps{
      sh 'echo "building the app"'
    }}
  stage('test'){
    steps{
      sh 'echo "runnning test"'
    }}
  stage('deploye'){
    steps{
      sh 'echo "deployinh"'
    }}
}
post{
  success{
    bat 'echo "build success"'}
  failure{
    bat 'echo "build failure"'}
}
  
  
}
  
