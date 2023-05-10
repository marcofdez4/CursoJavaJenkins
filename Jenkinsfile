pipeline {
    agent any

    stages {
        stage('Operaciones') {

            steps {
                script {
                    numero1 = 4
                    numero2 = 6
                }
                echo 'Declaracion de variables'
                println "numero 1: " + numero1
                println "numero 2: " + numero2
            }
        }
        stage('suma') {
            steps {
                script {
                      numeroSuma = numero1 + numero2
                }
                println "suma: " + numeroSuma
            }
        }
        stage('resta') {
            steps {
                script {
                    numeroResta = numero1 - numero2
                }
                println "resta: " + numeroResta
            }
        }
        stage('multiplicacion') {
            steps {
                script {
                    numeroMultiplicacion = numero1 * numero2
                }
                println "multiplicacion: " + numeroMultiplicacion
            }
        }
        stage('division') {
            steps {
                script {
                    if (numero2 == 0) {
                        echo 'no se puede dividir entre 0'
                    } else {
                        numeroDivision = numero1 / numero2
                        println "division: " + numeroDivision
                    }
                    
                } 
                
            }
        }
        
    }
}
