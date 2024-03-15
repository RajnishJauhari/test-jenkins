pipeline{
    agent any

    parameters{
        booleanParam(name:'IS_IT_OK', defaultValue:'false')
        choice(name:'PLAN_AFTER_MARRIAGE', choices:['HONEYMOON','PARTY', 'BREAK'])
    }

    stages {
    stage('Print Values') {
      steps {
        script{
        echo " Is it okay ${params.IS_IT_OK}"
        echo " The plan after marriage is ${params.IS_IT_OK}"
        }
      }
    }
  }
}