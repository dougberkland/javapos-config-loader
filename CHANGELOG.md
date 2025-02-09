# Change Log for javapos-config-loader

## 3.0.0

- requires Java 8 runtime (therefore the major version change)
- publishes to MavenCentral only, not Bintray (as Bintray has been shut down)
- added missing device catgeories to _jpos/res/jcl.dtd_ to be UnifiedPOS 1.14 compliant (solved [#3](https://github.com/JavaPOSWorkingGroup/javapos-config-loader/issues/3), contribution by [mjpcger](https://github.com/mjpcger))
- switched to MavenCentral publishing after Bintray's JCenter has been shut down (solved [#5](https://github.com/JavaPOSWorkingGroup/javapos-config-loader/issues/5))
- added this change log

## 2.3.1

- this release has the same content as the 2.3.0 release but has the version corrected in the manifest file.

## 2.3.0

- his release corresponds to JCL version 2.3.0-RC3 as provided by https://sourceforge.net/projects/jposloader/files/jcl/2.3.0-RC3/jcl2.3.0-RC3.zip/download except for one interface class, which has been moved to javapos-contracts (but, which has not been changed since the first release); and all editor sources.

## 2.2.0

- this release corresponds to JCL version 2.2.0 as provided by https://sourceforge.net/projects/jposloader/files/jcl/2.2.0/jcl2.2.0.zip except for one interface class, which has been moved to javapos-contracts