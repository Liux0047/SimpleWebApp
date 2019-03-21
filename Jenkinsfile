node {
   stage('Preparation') {
      git 'https://github.com/liux0047/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
   stage('Deploy') {
      sh "git push https://git.heroku.com/radiant-castle-41376.git"
   }
}