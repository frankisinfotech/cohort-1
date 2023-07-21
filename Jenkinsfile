pipeline {
    agent any
    stages {
        stage ('Get Env Variables'){
            steps {
              sh 'printenv'
            }
        }
        stage ('Git Version'){
            steps {
              sh 'git version'
            }
        }
        stage ('Docker Version'){
            steps {
              sh 'docker version'
            }
        }
        stage ('Maven Version'){
            steps {
              sh 'mvn -v'
            }
        }
    }
}
