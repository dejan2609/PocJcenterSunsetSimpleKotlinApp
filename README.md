POC for JCenter -->> Maven Central switch
=================


Just checkout some tags and refresh project like this:

* press 'Sync Project with Gradle Files' in the upper right corner (a.k.a elephant button) AND
* execute gradle command like this: ./gradlew --refresh-dependencies

Note: these two basically should boil to a same thing (but at the moment we are hunting bugs, so we need to crosscheck as much as we could).

Related external links:

* https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter
* https://www.infoq.com/news/2021/02/jfrog-jcenter-bintray-closure
* https://issuetracker.google.com/issues/179291081 com.android.tools:sdk-common needs to update its dependency on trove4j
* https://youtrack.jetbrains.com/issue/IDEA-261387 Move org.jetbrains.trove4j:trove4j:20160824 to MavenCentral

android studio details:
* Android Studio 4.2 Beta 4
* Build #AI-202.7660.26.42.7094744, built on January 21, 2021





