node{

stage (‘scm checkout’) {

git ‘https://github.com/<github repo>'

}

}

node{

stage (‘scm checkout’) {

git (‘https://github.com/jen-app-try')

}

stage (‘package stage’) {

sh label: ‘’, script: ‘mvn clean package ‘

}

}

     
