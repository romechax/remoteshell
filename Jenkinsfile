def remote = [:]
    remote.name = 'target2'
    remote.host = '13.233.32.176'
    remote.user = 'ec2-user'
    remote.allowAnyHosts = true
    stage('Remote SSH') {
      sshCommand remote: remote, command: "ls -lrt"
         }
