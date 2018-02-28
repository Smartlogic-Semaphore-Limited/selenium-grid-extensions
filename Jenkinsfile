library 'smartlogic-common'
smartlogic.buildInDocker('maven:3.5.2') {
  sh 'mvn verify -B'
  archiveArtifacts '**/target/*.jar'
}

