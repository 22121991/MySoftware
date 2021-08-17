properties([pipelineTriggers([pollSCM('0,30 * * * * ')])])
node{
  stage('one'){
    run("click().py")
  }
}
