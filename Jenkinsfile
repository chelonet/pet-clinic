pipeline {
    agent any  
    stages {

      stage('HOLA MUNDO') {
        steps {
          figlet 'HOLA-MUNDO'
          script {
            int[] array = [0,1,2,3] 
		
            for(int i=0; i < 3; i++){
                println("Hola ${i}") 
            }         
          }
        }
      }

    }
  }
}
