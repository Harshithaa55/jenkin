pipeline {
  agent any

   stages {

     stage('clone') {
       steps {
         git url: 'https://github.com/Harshithaa55/jenkin.git',
           branch: 'main'
       }
     }
     stage('Run script') {
       steps {
         sh 'chmod +x script.sh'
       }
     }
   }
}

    
