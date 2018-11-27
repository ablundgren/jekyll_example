pipeline {
  agent any
    stages {
      stage('Build') {
        steps {
          awsCodeBuild projectName: 'reinvent-2018-lundgren',
                       credentialsId: '	69eea4d9-23fe-42f8-b2ad-94deca97af4a',
                       credentialsType: 'jenkins',
                       region: 'us-east-1',
                       sourceControlType: 'project'

        }
      }
    }
}
