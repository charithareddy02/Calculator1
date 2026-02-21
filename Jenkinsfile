pipeline{
agent any
stages{
stage('Clone'){
steps{
git branch:'main',url:'https://github.com/charithareddy02/Calculator1.git';
}
}
stage('Complile'){
stepa{
sh 'javac Calculator.java'
}
}
stage('Build'){
steps{
sh 'java Calculator 25 5'
}
}
stage('Test'){
steps{
sh 'java Calculator 30 -5'
}
}
stage('Deploy'){
stepa{
echo 'Deployment completed'
}
}
}
}
