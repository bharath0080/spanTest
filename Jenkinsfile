pipeline{
    agent{
        label any
    }
    stages{
        stage('test'){
            script{
                sh "echo okkkkkk > test.txt "
            def loading = load 'test.groovy'
            loading.testing()
            }
        }
    }
}
