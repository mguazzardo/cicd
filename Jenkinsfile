node {
         stage('build') {
           openshiftBuild(buildConfig: 'pruebacicd', showBuildLogs: 'true')
         }
         stage('test') {
           sh('''python --version;''')
         }
  }
