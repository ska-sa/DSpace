#!groovy

@Library('katsdpjenkins') _
katsdp.killOldJobs()

katsdp.stagePrepare()
katsdp.stageMakeDocker(dockerImage:'dspace', filename: 'Dockerfile.jdk8-test', venv:false)

katsdp.mail('cschollar@ska.ac.za')
