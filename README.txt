This illustrates an issue with Gradle's "idea"-plugin.
The plugin does not properly resolve dependencies to the latest referenced version, instead adding each of the versions to IntelliJ IDEA's project.

See http://stackoverflow.com/questions/8989311/can-i-get-gradles-idea-plugin-resolve-to-newest-version-for-dependencies for details and discussion.
