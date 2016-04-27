#Simple android project starter

There is an issue with new gradle tools (>= 2.0.0):

<code>
Error:Execution failed for task ':mockableAndroidJar'.
java.lang.NullPointerException (no error message)
</code>

To avoid this in Android Studio (>= 2.0.0), go to "Files->Settings->Build,Execution,Deployment->Build Tools->Gradle->Experimental" and uncheck "Enable all test artifacts (Unit Test and Instrumentation Test) in Android projects"
