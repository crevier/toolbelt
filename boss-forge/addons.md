Jboss forge addons
==================

this document contains a list of the jboss forge addon I like with their commands and how to install them.

**using old version of forge can cause problems with some of the addons. I used the 3.1.1.Final**

Gradle
------

The [gradle addon](https://forge.jboss.org/addon/org.jboss.forge.addon:dependencies) profide gradle support for jboss-forge
 
### Installation

In forge :
for the last stable version

    addon-install --coordinate org.jboss.forge.addon:gradle,2.12.2.Final

for the last version

    addon-install-from-git --url https://github.com/forge/addon-gradle.git --coordinate org.jboss.forge.addon:gradle 

### Usages

This addon provide the `Gradle` value for the `--build-system` option of the `project-new`command.

It seems that the addon is not working currently... 

    ***ERROR*** Error while executing 'Project: New'
    ***INFO*** (type "export VERBOSE=true" to enable stack traces)
    ***ERROR*** Facet type [org.jboss.forge.addon.gradle.projects.facets.GradleJavaCompilerFacet] could not be installed into [org.jboss.forge.addon.gradle.projects.GradleProject@50ef1fa8] of type [org.jboss.forge.addon.gradle.projects.GradleProject]. You may wish to check for inconsistent origin state as partial installation may have occurred.

