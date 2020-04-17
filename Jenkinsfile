pipeline {
    agent any
    stages {
        stage("Build") {
            when {
               buildingTag()

            }
            steps {
                echo "Building on buildingTag"
            }
        }
    }
}
