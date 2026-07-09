node {
    stage('Git-clone') { // for display purposes
        // Get some code from a GitHub repository
        git 'https://github.com/MonikhaKandaswamy/java.git'
    }
    stage('java-commands') {
        // Run the build. You must have Maven installed.
        bat '''javac Test.java
            java Test.java'''
        }
}