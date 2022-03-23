//Declarativa: es más cómoda, menos flexible
pipeline {
    
    agent any;
    
    stages {
        stage('Compilacion'){
            steps {
                echo 'Voy a compilar:'
                echo 'Estoy en ello...'
                echo 'Listo'
            }
            //tanto la maarca post como las marcas de dentro son opcionales
            post {
                success{
                    echo 'Se ejecuta solo si los steps han ido bien'
                    
                }
                failure{
                    echo 'Se ejecuta solo si los steps han ido mal'
                    
                }
                always{
                    echo 'Se ejecuta siempre'
                    
                }
            }
        }
         stage('Pruebas'){
            steps {
                echo 'Voy a probar:'
                echo 'Estoy en ello...'
                echo 'Listo'
            }
            //tanto la maarca post como las marcas de dentro son opcionales
            post {
                success{
                    echo 'Se ejecuta solo si los steps han ido bien'
                    
                }
                failure{
                    echo 'Se ejecuta solo si los steps han ido mal'
                    
                }
                always{
                    echo 'Se ejecuta siempre'
                    
                }
            }
        }
    }
}

//scriipted: más potente, más flexible, menos cómoda