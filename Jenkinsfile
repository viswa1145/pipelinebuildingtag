pipeline {
    agent any
    stages {
        stage("Build") {
            when {
               changeRequest title: 'when-pr'

            }
            steps {
                echo "Building on when pr"
            }
        }
    }
}
