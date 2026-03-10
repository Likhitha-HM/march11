pipeline {
    agent any
    stages {
        stage('Clone') {
           steps {
              git url: 'https://github.com/Likhitha-HM/march11.git',
              branch: 'main'
       }
}
stage('Run Script') {
   steps {
       sh 'chmod +x script.sh'
       sh './script.sh'
     }
  }
 }
}
