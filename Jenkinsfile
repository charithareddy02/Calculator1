pipeline{
agent any
stages{
stage('clone'){
steps{
git branch:'main',url:'https://github.com/charithareddy02/Calculator1.git';
}
}
stage('complile'){
stepa{
sh 'javac Calculator.java'
}
}
stage('build'){
steps{
sh 'java Calculator 25 5'
}
}
stage('test'){
steps{
sh 'java Calculator 30 -5'
}
}
stage('deploy'){
stepa{
echo 'Deployment completed'
}
}
}
}
