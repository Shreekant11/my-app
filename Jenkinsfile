node{
stage('SVM Checkout')
{
git 'https://github.com/Shreekant11/my-app.git'
}
stage('Compile Package')
{
def mvnHome=tool name: 'maven', type: 'maven'
sh 'mvn package'
}
}
