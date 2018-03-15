
node {
    def mvnHome
    stage('codecheckout')
    git 'https://github.com/Ajayk2009/course.git'
    mvnHome = tool 'Maven_Home'
    stage('compilation')
     sh "'${mvnHome}/bin/mvn' compile"
    stage('Package')
     sh "'${mvnHome}/bin/mvn' package" 
    stage('Result')
     echo 'Successfull'
}
