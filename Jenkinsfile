pipeline {
agent {label 'DEV'}
stages {
stage('scm'){
steps{checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '3c5f6437-1ab4-4e88-bfa1-82d83a88b75b', url: 'https://github.com/rafi4Devops1/mavenrepo.git']]])
} // steps close
} // stage1 close
} // stages close
} //pipeline close
