pipeline {
    agent {
        node {
            label 'master'
        }
    }
    //parameters {
    //    string(name: 'user_id', defaultValue: 'gilver.souza', description: 'Id do usuário.')
    //    string(name: 'api_name', defaultValue: 'api-user', description: 'Nome da API.')
    //}
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
