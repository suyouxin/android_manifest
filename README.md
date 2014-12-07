android_manifest
================
Android 5.0 for XO-4 is in active development status. Any contribution would be much appreciated.

Currently the graphics are almost working. Developers are welcomed to peek/compile the repositories.  04/12/2014.

* use Repo to download the Android source from github repositories.

 $ repo init -u git://github.com/suyouxin/android_manifest.git -b android-5.0.0-xo4
 $ repo sync

* Note: only engineer build is usable, user build can't be booted since [https://source.android.com/devices/tech/security/se-linux.html SELinux] feature hasn't been adapted.

== Test build==
  A test build can be downloaded here, [http://dev.laptop.org/~ben/android50.zd testbuild]
