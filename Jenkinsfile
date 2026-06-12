pipeline {
    agent any

    stages {
        stage("Build Info") {
            steps {
                echo "Build triggered successfully"
                echo "Branch: ${env.GIT_BRANCH}"
                echo "Commit: ${env.GIT_COMMIT}"
                echo "Repo: ${env.GIT_URL}"
            }
        }
    }
}
