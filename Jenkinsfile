pelineJob('task-1') {
  definition {
    cps {
      script("""
        pipeline {
          agent any
          stages {
            stage('Build') {
              steps {
                sh 'echo "Build stage kesava"'
              }
            }
            stage('Test') {
              steps {
                sh 'echo "Test stage kesava"'
              }
            }
            stage('Deploy') {
              steps {
                sh 'echo "Deploy stage kesava"'
              }
            }
          }
        }
      """)
    }
  }
}
