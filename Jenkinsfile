// Declarativa: Es más cómoda... más guiada... menos flexible
pipeline {
    
    agent any;
    
    stages {
        stage('Compilación') {
            steps {
                echo 'Voy a compilar...'
                echo 'Estoy en ello...'
                echo 'Listo'
            }
            post {
                success {
                    echo 'Se ejecuta solo si los steps han ido bien'
                }
                failure {
                    echo 'Se ejecuta solo si los steps han ido mal'
                }
                always {
                    echo 'Se ejecuta en cualquier caso'
                }
            }
        }
        stage('Pruebas') {
            steps {
                echo 'Voy a compilar...'
                echo 'Estoy en ello...'
                echo 'Listo'
            }
            post {
                success {
                    echo 'Se ejecuta solo si los steps han ido bien'
                }
                failure {
                    echo 'Se ejecuta solo si los steps han ido mal'
                }
                always {
                    echo 'Se ejecuta en cualquier caso'
                }
            }
        }
    }
    
    // Parte posterior
    
    post {
                success {
                    echo 'Se ejecuta solo si los steps han ido bien'
                }
                failure {
                    echo 'Se ejecuta solo si los steps han ido mal'
                
}

// Scripted: Es más potente, más fiable... menos cómoda. LA BUENA !!