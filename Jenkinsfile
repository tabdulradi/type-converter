node('sbt-slave') {
  ansiColor('xterm') {
    stage('Compile') {
      sh "sbt ';compile ;test:compile'"
    }
    stage('Test') {
      sh "sbt test"
    }
  }
}