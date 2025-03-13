pipeline {
    stages {
        stage('Run only on main branch') {
            when {
                expression { return env.ref == 'refs/heads/main' }
            }
            steps {
                echo "Main branch updated. Running pipeline..."
            }
        }
    }
}