pipeline {
    agent any
    environment {
        JAVA_VERSION = "11.0"
        JAVA_PATH = "/usr/sbin/java"
    }
    stages {
        stage ("welcome to dvs") {
            steps {
                script {
                    var1=44
                    var2="sameekshya"
                    println "myvar1 value is ${var1} and myvar2 value is ${var2}"
                    println "my workspace is ${WORKSPACE}"
                    println "my build number is ${BUILD_NUMBER}"
                    println "my java version is ${env.JAVA_VERSION}"
                    println "my java path is ${env.JAVA_PATH}"
                }
            }
        }
    }
}
