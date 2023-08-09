pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh ''' cd ../../../../..
 cd home/sam-admin/\\\'Untitled Folder 1\\\'
 g++ binary.cpp'''
      }
    }

    stage('test') {
      steps {
        sh '''cd ../../../../..
cd home/sam-admin/\\\'Untitled Folder 1\\\'
./a.out'''
      }
    }

  }
}