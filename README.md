# Description
This is a template for a multi project gradle build for minecraft forge modding.
There may be some things that aren't correct, as I'm not that into Gradle. If you are and find an error please create an issue.

# How to use it
The first thing you may want to do is set the project name in the settings.gradle

1. Put your forge projects into subprojects
2. Include your projects in the settings.gradle (e.g.: "include subprojects:AttackonMinecraft")
3. Make sure all your projects have "publish.dependsOn('reobfJar')" not commented in their build.gradle
