# Change Log

## 0.2.3 - 2016-01-13

* Compatible with Java 7 and 8. 
* Add `-P java6` use it with Java 6. The `java6` profile will be removed in the near future.
* Add `versions-maven-plugin` to make it easier to upgrade plugins.
* Plugin updates.


    maven-failsafe-plugin .............................. 2.18.1 -> 2.19.1
    maven-pmd-plugin ......................................... 3.5 -> 3.6
    maven-project-info-reports-plugin ...................... 2.8 -> 2.8.1
    maven-surefire-plugin .............................. 2.18.1 -> 2.19.1
    maven-surefire-report-plugin ....................... 2.18.1 -> 2.19.1
    org.codehaus.mojo:findbugs-maven-plugin .............. 2.5.5 -> 3.0.3
    org.sonatype.plugins:nexus-staging-maven-plugin ...... 1.6.5 -> 1.6.6


## 0.2.2 - 2015-09-15

* Downgrade JaCoCo from 0.7.5.201505241946 to 0.7.4.201502262128 because the coverage reports won't show up in Jenkins.
            
## 0.2.1 - 2015-07-23

* Enable `noJekyll` option in GitHub Site Plugin to allow JaCoCo web reports to show up properly in GitHub pages.

## 0.2.0 - 2015-07-23

* Attach `site:attach-descriptor` in Maven Site Plugin to allow Maven 3 to pick up `src/site/site.xml`.

## 0.1.0 - 2015-07-22

* Initial.