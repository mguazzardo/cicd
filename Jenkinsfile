node {
         stage('build') {
           openshiftBuild(buildConfig: 'myprojectname', showBuildLogs: 'true')
         }
         stage('test') {
           sh('''python --version;''')
         }
  }
