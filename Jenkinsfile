pipeline {
    agent any

    stages {
        stage("Check PR") {
            steps {
                echo "Event: ${env.pr_event}"
                echo "PR: ${env.approved_pr}"
                echo "User: ${env.approved_user}"
                echo "Repo: ${env.pr_repo_name}"
            }
        }
    }
}
