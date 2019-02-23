pipeline{
    agent{
        label 'master'
    }
    stages{
        stage('test'){
            steps{
            script{
                sh "echo okkkkkk > test.txt "
            def loading = load 'test.groovy'
            loading.testing()
            }
            }
        }
    }
}
