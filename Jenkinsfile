pipeline{
    agent{
        label 'master'
    }
    stages{
        stage('test'){
            steps{
            script{
                bat "echo okkkkkk > test.txt "
            def loading = load 'test.groovy'
            loading.testing()
            }
            }
        }
    }
}
