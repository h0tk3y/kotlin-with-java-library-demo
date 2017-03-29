# kotlin-with-java-library-demo
A minimal demo project for Kotlin with Gradle java-library plugin

The `lib` project is build with the `java-library` plugin, and its dependency `implementation "...:kotlin-reflect:1.1.1"` does not
leak into the `app` module compile classpath.
