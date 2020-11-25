pipeline {
    agent {
        node {
            label 'master'
        }
    }
    parameters {
      choice(name: 'Environment',
      choices: [
        'dev',
        'hml',
        'prd'
        ]
      )
    }
    stages {
        stage('Stage 01') { 
            steps {
                sh 'ls' 
            }
        }
        //stage('Stage 02') { 
        //    steps {
        //        echo "${user_id}"
        //        echo "${api_name}"
        //    }
        //}
    }
}
