node{
    stage('clone java code') {
   git 'https://github.com/ssfvc/mahalogin.git'
    }
    
    
    stage('maven targets') {
    sh label: '', script: 'mvn install'
    }
     
}
