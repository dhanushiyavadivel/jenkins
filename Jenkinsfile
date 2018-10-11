Pipeline {
     agent any
     stages {
          stage('build') {
               steps {
                   sh 'echo "hello world"'
                   sh '''
                       echo "multiple shell stpe works too"
                       ls -lah
                    '''
                }
          }
      }
}

