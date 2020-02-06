pipeline{
agent any
stages{

stage('Jenkins job'){
 steps {
 sh '''
  curl --request GET \
  --url 'http://ec2-18-191-16-16.us-east-2.compute.amazonaws.com:8080/rest/api/2/dashboard' \
  --user 'rig:cmlnOmRpZ2l0YWxyaWdAMTIz' \
  --header 'Accept: application/json'
 '''
 }
 }
 }
 }
 
