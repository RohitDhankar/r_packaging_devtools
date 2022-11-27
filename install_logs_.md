


#
> --------------------------- [ANTICONF] --------------------------------
Configuration failed to find the harfbuzz freetype2 fribidi library. Try installing:
 * deb: libharfbuzz-dev libfribidi-dev (Debian, Ubuntu, etc)

#

> OK Done Install - DevTools 
- install.packages("devtools")
- installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-textshaping/00new/textshaping/libs
- installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-ragg/00new/ragg/libs



#


```bash

> install.packages("devtools")
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
also installing the dependencies ‘textshaping’, ‘ragg’, ‘pkgdown’

trying URL 'https://cloud.r-project.org/src/contrib/textshaping_0.3.6.tar.gz'
Content type 'application/x-gzip' length 35722 bytes (34 KB)
==================================================
downloaded 34 KB

trying URL 'https://cloud.r-project.org/src/contrib/ragg_1.2.4.tar.gz'
Content type 'application/x-gzip' length 427579 bytes (417 KB)
==================================================
downloaded 417 KB

trying URL 'https://cloud.r-project.org/src/contrib/pkgdown_2.0.6.tar.gz'
Content type 'application/x-gzip' length 871371 bytes (850 KB)
==================================================
downloaded 850 KB

trying URL 'https://cloud.r-project.org/src/contrib/devtools_2.4.5.tar.gz'
Content type 'application/x-gzip' length 374718 bytes (365 KB)
==================================================
downloaded 365 KB

* installing *source* package ‘textshaping’ ...
** package ‘textshaping’ successfully unpacked and MD5 sums checked
** using staged installation
Found pkg-config cflags and libs!
Using PKG_CFLAGS=-I/usr/include/harfbuzz -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/fribidi
Using PKG_LIBS=-lharfbuzz -lfreetype -lfribidi
** libs
rm -f textshaping.so cpp11.o face_feature.o hb_shaper.o init.o string_bidi.o string_metrics.o string_shape.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -DNDEBUG -I/usr/include/harfbuzz -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/fribidi -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c cpp11.cpp -o cpp11.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -DNDEBUG -I/usr/include/harfbuzz -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/fribidi -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c face_feature.cpp -o face_feature.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -DNDEBUG -I/usr/include/harfbuzz -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/fribidi -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c hb_shaper.cpp -o hb_shaper.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -DNDEBUG -I/usr/include/harfbuzz -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/fribidi -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c init.cpp -o init.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -DNDEBUG -I/usr/include/harfbuzz -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/fribidi -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c string_bidi.cpp -o string_bidi.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -DNDEBUG -I/usr/include/harfbuzz -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/fribidi -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c string_metrics.cpp -o string_metrics.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -DNDEBUG -I/usr/include/harfbuzz -I/usr/include/glib-2.0 -I/usr/lib/x86_64-linux-gnu/glib-2.0/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/fribidi -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c string_shape.cpp -o string_shape.o
g++ -std=gnu++11 -shared -L/usr/lib/R/lib -Wl,-Bsymbolic-functions -Wl,-z,relro -o textshaping.so cpp11.o face_feature.o hb_shaper.o init.o string_bidi.o string_metrics.o string_shape.o -lharfbuzz -lfreetype -lfribidi -L/usr/lib/R/lib -lR
installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-textshaping/00new/textshaping/libs
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (textshaping)
* installing *source* package ‘ragg’ ...
** package ‘ragg’ successfully unpacked and MD5 sums checked
** using staged installation
Found pkg-config cflags and libs!
Using PKG_CFLAGS=-I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu
Using PKG_LIBS=-lfreetype -lpng16 -lz -ltiff -ljpeg
** libs
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c capture_dev.cpp -o capture_dev.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c init.cpp -o init.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c jpeg_dev.cpp -o jpeg_dev.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c png_dev.cpp -o png_dev.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c ppm_dev.cpp -o ppm_dev.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c tiff_dev.cpp -o tiff_dev.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c agg/src/agg_curves.cpp -o agg/src/agg_curves.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c agg/src/agg_font_freetype.cpp -o agg/src/agg_font_freetype.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c agg/src/agg_image_filters.cpp -o agg/src/agg_image_filters.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c agg/src/agg_trans_affine.cpp -o agg/src/agg_trans_affine.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c agg/src/agg_vcgen_dash.cpp -o agg/src/agg_vcgen_dash.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG  -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/systemfonts/include' -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping/include'   -I./agg/include -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/x86_64-linux-gnu -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c agg/src/agg_vcgen_stroke.cpp -o agg/src/agg_vcgen_stroke.o
ar rcs agg/libstatagg.a agg/src/agg_curves.o agg/src/agg_font_freetype.o agg/src/agg_image_filters.o agg/src/agg_trans_affine.o agg/src/agg_vcgen_dash.o agg/src/agg_vcgen_stroke.o
g++ -std=gnu++11 -shared -L/usr/lib/R/lib -Wl,-Bsymbolic-functions -Wl,-z,relro -o ragg.so capture_dev.o init.o jpeg_dev.o png_dev.o ppm_dev.o tiff_dev.o -Lagg -lstatagg -lfreetype -lpng16 -lz -ltiff -ljpeg -L/usr/lib/R/lib -lR
installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-ragg/00new/ragg/libs
** R
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (ragg)
* installing *source* package ‘pkgdown’ ...
** package ‘pkgdown’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (pkgdown)
* installing *source* package ‘devtools’ ...
** package ‘devtools’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (devtools)

The downloaded source packages are in
	‘/tmp/RtmpYvsHJW/downloaded_packages’
> library(devtools)
Loading required package: usethis
Registered S3 methods overwritten by 'callr':
  method                    from
  format.callr_status_error     
  print.callr_status_error      
> 
```


```bash
(base) dhankar@dhankar-1:~/.../r_packaging_devtools$ sudo apt-get install -y libharfbuzz-dev libxml2-dev libfontconfig1-dev libicu-dev libcurl4-openssl-dev libssl-dev  libpng-dev libtiff-dev libjpeg-dev
[sudo] password for dhankar: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
libfontconfig1-dev is already the newest version (2.12.6-0ubuntu2).
libfontconfig1-dev set to manually installed.
libharfbuzz-dev is already the newest version (1.7.2-1ubuntu1).
libjpeg-dev is already the newest version (8c-2ubuntu8).
libicu-dev is already the newest version (60.2-3ubuntu3.2).
libicu-dev set to manually installed.
libpng-dev is already the newest version (1.6.34-1ubuntu0.18.04.2).
libssl-dev is already the newest version (1.1.1-1ubuntu2.1~18.04.20).
libtiff-dev is already the newest version (4.0.9-5ubuntu0.8).
The following packages were automatically installed and are no longer required:
  cdbs dh-translations intltool jq libappindicator1 libindicator7 libjq1 libonig4 linux-hwe-5.4-headers-5.4.0-100
  linux-hwe-5.4-headers-5.4.0-104 linux-hwe-5.4-headers-5.4.0-105 linux-hwe-5.4-headers-5.4.0-107 linux-hwe-5.4-headers-5.4.0-109
  linux-hwe-5.4-headers-5.4.0-110 linux-hwe-5.4-headers-5.4.0-126 linux-hwe-5.4-headers-5.4.0-128 linux-hwe-5.4-headers-5.4.0-47
  linux-hwe-5.4-headers-5.4.0-48 linux-hwe-5.4-headers-5.4.0-51 linux-hwe-5.4-headers-5.4.0-52 linux-hwe-5.4-headers-5.4.0-58
  linux-hwe-5.4-headers-5.4.0-60 linux-hwe-5.4-headers-5.4.0-62 linux-hwe-5.4-headers-5.4.0-65 linux-hwe-5.4-headers-5.4.0-66
  linux-hwe-5.4-headers-5.4.0-67 linux-hwe-5.4-headers-5.4.0-70 linux-hwe-5.4-headers-5.4.0-72 linux-hwe-5.4-headers-5.4.0-73
  linux-hwe-5.4-headers-5.4.0-74 linux-hwe-5.4-headers-5.4.0-77 linux-hwe-5.4-headers-5.4.0-80 linux-hwe-5.4-headers-5.4.0-81
  linux-hwe-5.4-headers-5.4.0-84 linux-hwe-5.4-headers-5.4.0-86 linux-hwe-5.4-headers-5.4.0-87 linux-hwe-5.4-headers-5.4.0-89
  linux-hwe-5.4-headers-5.4.0-90 linux-hwe-5.4-headers-5.4.0-91 linux-hwe-5.4-headers-5.4.0-92 linux-hwe-5.4-headers-5.4.0-94
  linux-hwe-5.4-headers-5.4.0-96 linux-hwe-5.4-headers-5.4.0-97 linux-hwe-5.4-headers-5.4.0-99 python3-scour scour
Use 'sudo apt autoremove' to remove them.
Suggested packages:
  libcurl4-doc libidn11-dev libkrb5-dev librtmp-dev libssh2-1-dev
The following packages will be REMOVED:
  libcurl4-gnutls-dev
The following NEW packages will be installed:
  libcurl4-openssl-dev libxml2-dev
0 upgraded, 2 newly installed, 1 to remove and 225 not upgraded.
Need to get 1,060 kB of archives.
After this operation, 3,568 kB of additional disk space will be used.
Get:1 http://in.archive.ubuntu.com/ubuntu bionic-updates/main amd64 libcurl4-openssl-dev amd64 7.58.0-2ubuntu3.21 [302 kB]
Get:2 http://in.archive.ubuntu.com/ubuntu bionic-updates/main amd64 libxml2-dev amd64 2.9.4+dfsg1-6.1ubuntu1.7 [757 kB]
Fetched 1,060 kB in 2s (642 kB/s)    
(Reading database ... 993755 files and directories currently installed.)
Removing libcurl4-gnutls-dev:amd64 (7.58.0-2ubuntu3.21) ...
Selecting previously unselected package libcurl4-openssl-dev:amd64.
(Reading database ... 993734 files and directories currently installed.)
Preparing to unpack .../libcurl4-openssl-dev_7.58.0-2ubuntu3.21_amd64.deb ...
Unpacking libcurl4-openssl-dev:amd64 (7.58.0-2ubuntu3.21) ...
Selecting previously unselected package libxml2-dev:amd64.
Preparing to unpack .../libxml2-dev_2.9.4+dfsg1-6.1ubuntu1.7_amd64.deb ...
Unpacking libxml2-dev:amd64 (2.9.4+dfsg1-6.1ubuntu1.7) ...
Setting up libxml2-dev:amd64 (2.9.4+dfsg1-6.1ubuntu1.7) ...
Setting up libcurl4-openssl-dev:amd64 (7.58.0-2ubuntu3.21) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
(base) dhankar@dhankar-1:~/.../r_packaging_devtools$ 
(base) dhankar@dhankar-1:~/.../r_packaging_devtools$ 

```

```bash
	‘/tmp/RtmpYvsHJW/downloaded_packages’
> pak::pkg_system_requirements("pkgdown", "ubuntu", "20.04")
libfontconfig1-dev libicu-dev libcurl4-openssl-dev libssl-dev  libpng-dev libtiff-dev libjpeg-dev

 [1] "apt-get install -y libfreetype6-dev"     "apt-get install -y libfribidi-dev"      
 [3] "apt-get install -y libharfbuzz-dev"      "apt-get install -y libxml2-dev"         
 [5] "apt-get install -y make"                 "apt-get install -y libfontconfig1-dev"  
 [7] "apt-get install -y libicu-dev"           "apt-get install -y pandoc"              
 [9] "apt-get install -y libcurl4-openssl-dev" "apt-get install -y libssl-dev"          
[11] "apt-get install -y libjpeg-dev"          "apt-get install -y libpng-dev"          
[13] "apt-get install -y libtiff-dev"         

libxml2-dev

> pak::pkg_system_requirements("devtools", "ubuntu", "20.04")
 [1] "apt-get install -y libfreetype6-dev"     "apt-get install -y libfribidi-dev"      
 [3] "apt-get install -y libharfbuzz-dev"      "apt-get install -y git"                 
 [5] "apt-get install -y libxml2-dev"          "apt-get install -y make"                
 [7] "apt-get install -y libfontconfig1-dev"   "apt-get install -y libicu-dev"          
 [9] "apt-get install -y pandoc"               "apt-get install -y zlib1g-dev"          
[11] "apt-get install -y libgit2-dev"          "apt-get install -y libcurl4-openssl-dev"
[13] "apt-get install -y libssl-dev"           "apt-get install -y libjpeg-dev"         
[15] "apt-get install -y libpng-dev"           "apt-get install -y libtiff-dev"         
```





```bash
(base) dhankar@dhankar-1:~/.../#Rstats$ sudo apt-get install libharfbuzz-dev libfribidi-dev libfreetype6-dev
[sudo] password for dhankar: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
libharfbuzz-dev is already the newest version (1.7.2-1ubuntu1).
libharfbuzz-dev set to manually installed.
libfreetype6-dev is already the newest version (2.8.1-2ubuntu2.2).
libfreetype6-dev set to manually installed.
The following packages were automatically installed and are no longer required:
  cdbs dh-translations intltool jq libappindicator1 libindicator7 libjq1 libonig4 linux-hwe-5.4-headers-5.4.0-100
  linux-hwe-5.4-headers-5.4.0-104 linux-hwe-5.4-headers-5.4.0-105 linux-hwe-5.4-headers-5.4.0-107 linux-hwe-5.4-headers-5.4.0-109
  linux-hwe-5.4-headers-5.4.0-110 linux-hwe-5.4-headers-5.4.0-126 linux-hwe-5.4-headers-5.4.0-128 linux-hwe-5.4-headers-5.4.0-47
  linux-hwe-5.4-headers-5.4.0-48 linux-hwe-5.4-headers-5.4.0-51 linux-hwe-5.4-headers-5.4.0-52 linux-hwe-5.4-headers-5.4.0-58
  linux-hwe-5.4-headers-5.4.0-60 linux-hwe-5.4-headers-5.4.0-62 linux-hwe-5.4-headers-5.4.0-65 linux-hwe-5.4-headers-5.4.0-66
  linux-hwe-5.4-headers-5.4.0-67 linux-hwe-5.4-headers-5.4.0-70 linux-hwe-5.4-headers-5.4.0-72 linux-hwe-5.4-headers-5.4.0-73
  linux-hwe-5.4-headers-5.4.0-74 linux-hwe-5.4-headers-5.4.0-77 linux-hwe-5.4-headers-5.4.0-80 linux-hwe-5.4-headers-5.4.0-81
  linux-hwe-5.4-headers-5.4.0-84 linux-hwe-5.4-headers-5.4.0-86 linux-hwe-5.4-headers-5.4.0-87 linux-hwe-5.4-headers-5.4.0-89
  linux-hwe-5.4-headers-5.4.0-90 linux-hwe-5.4-headers-5.4.0-91 linux-hwe-5.4-headers-5.4.0-92 linux-hwe-5.4-headers-5.4.0-94
  linux-hwe-5.4-headers-5.4.0-96 linux-hwe-5.4-headers-5.4.0-97 linux-hwe-5.4-headers-5.4.0-99 python3-scour scour
Use 'sudo apt autoremove' to remove them.
The following NEW packages will be installed:
  libfribidi-dev
0 upgraded, 1 newly installed, 0 to remove and 225 not upgraded.
Need to get 42.5 kB of archives.
After this operation, 152 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://in.archive.ubuntu.com/ubuntu bionic-updates/main amd64 libfribidi-dev amd64 0.19.7-2ubuntu0.1 [42.5 kB]
Fetched 42.5 kB in 1s (43.5 kB/s)         
Selecting previously unselected package libfribidi-dev.
(Reading database ... 993705 files and directories currently installed.)
Preparing to unpack .../libfribidi-dev_0.19.7-2ubuntu0.1_amd64.deb ...
Unpacking libfribidi-dev (0.19.7-2ubuntu0.1) ...
Setting up libfribidi-dev (0.19.7-2ubuntu0.1) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
(base) dhankar@dhankar-1:~/.../#Rstats$ 

```
#
```bash
’
> pak::pkg_system_requirements("pkgdown", "ubuntu", "20.04")
Error in loadNamespace(x) : there is no package called ‘pak’
> install.packages("pak")
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
trying URL 'https://cloud.r-project.org/src/contrib/pak_0.3.1.tar.gz'
Content type 'application/x-gzip' length 120022 bytes (117 KB)
==================================================
downloaded 117 KB

* installing *source* package ‘pak’ ...
** package ‘pak’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** data
*** moving datasets to lazyload DB
**** building pak dependency data, this can take several minutes
**** deps data (23): ..........10..........20...23
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (pak)

The downloaded source packages are in
	‘/tmp/RtmpYvsHJW/downloaded_packages’
```

> Lots of packages with Install EXIT Status as NON ZERO 
installation of package ‘textshaping’ had non-zero exit status


##### as recommended below - for Ubuntu need to update packages from - apt 
- https://github.com/r-lib/pkgdown/issues/1427

#
```bash

apt-get install libharfbuzz-dev libfribidi-dev libfreetype6-dev 

apt-get install libzmq3-dev libharfbuzz-dev libfribidi-dev libfreetype6-dev libpng-dev libtiff5-dev libjpeg-dev build-essential libcurl4-openssl-dev libxml2-dev libssl-dev libfontconfig1-dev

#
Package fribidi was not found in the pkg-config search path.
```
#


```bash

Installing 'devtools' ...
[1/10] Installing miniUI...
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
trying URL 'https://cloud.r-project.org/src/contrib/miniUI_0.1.1.1.tar.gz'
Content type 'application/x-gzip' length 97958 bytes (95 KB)
==================================================
downloaded 95 KB

* installing *source* package ‘miniUI’ ...
** package ‘miniUI’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
[2/10] Installing pkgbuild...
** testing if installed package keeps a record of temporary installation path
* DONE (miniUI)

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
trying URL 'https://cloud.r-project.org/src/contrib/pkgbuild_1.3.1.tar.gz'
Content type 'application/x-gzip' length 31937 bytes (31 KB)
==================================================
downloaded 31 KB

* installing *source* package ‘pkgbuild’ ...
** package ‘pkgbuild’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (pkgbuild)
[3/10] Installing pkgdown...

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
also installing the dependencies ‘brio’, ‘systemfonts’, ‘textshaping’, ‘downlit’, ‘ragg’

trying URL 'https://cloud.r-project.org/src/contrib/brio_1.1.3.tar.gz'
Content type 'application/x-gzip' length 12629 bytes (12 KB)
==================================================
downloaded 12 KB

trying URL 'https://cloud.r-project.org/src/contrib/systemfonts_1.0.4.tar.gz'
Content type 'application/x-gzip' length 81757 bytes (79 KB)
==================================================
downloaded 79 KB

trying URL 'https://cloud.r-project.org/src/contrib/textshaping_0.3.6.tar.gz'
Content type 'application/x-gzip' length 35722 bytes (34 KB)
==================================================
downloaded 34 KB

trying URL 'https://cloud.r-project.org/src/contrib/downlit_0.4.2.tar.gz'
Content type 'application/x-gzip' length 37039 bytes (36 KB)
==================================================
downloaded 36 KB

trying URL 'https://cloud.r-project.org/src/contrib/ragg_1.2.4.tar.gz'
Content type 'application/x-gzip' length 427579 bytes (417 KB)
==================================================
downloaded 417 KB

trying URL 'https://cloud.r-project.org/src/contrib/pkgdown_2.0.6.tar.gz'
Content type 'application/x-gzip' length 871371 bytes (850 KB)
==================================================
downloaded 850 KB

gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c brio.c -o brio.o
* installing *source* package ‘brio’ ...
** package ‘brio’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c file_line_endings.c -o file_line_endings.o
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c init.c -o init.o
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c read_file.c -o read_file.o
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c read_file_raw.c -o read_file_raw.o
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c read_lines.c -o read_lines.o
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c write_file.c -o write_file.o
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c write_file_raw.c -o write_file_raw.o
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c write_lines.c -o write_lines.o
gcc -shared -L/usr/lib/R/lib -Wl,-Bsymbolic-functions -Wl,-z,relro -o brio.so brio.o file_line_endings.o init.o read_file.o read_file_raw.o read_lines.o write_file.o write_file_raw.o write_lines.o -L/usr/lib/R/lib -lR
installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-brio/00new/brio/libs
** R
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (brio)
* installing *source* package ‘systemfonts’ ...
** package ‘systemfonts’ successfully unpacked and MD5 sums checked
** using staged installation
Found pkg-config cflags and libs!
Using PKG_CFLAGS=-I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16
Using PKG_LIBS=-lfontconfig -lfreetype
rm -f systemfonts.so caches.o cpp11.o dev_metrics.o font_matching.o font_registry.o ft_cache.o string_shape.o font_metrics.o font_fallback.o string_metrics.o emoji.o cache_store.o init.o unix/FontManagerLinux.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c caches.cpp -o caches.o
** libs
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c cpp11.cpp -o cpp11.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c dev_metrics.cpp -o dev_metrics.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c font_matching.cpp -o font_matching.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c font_registry.cpp -o font_registry.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c ft_cache.cpp -o ft_cache.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c string_shape.cpp -o string_shape.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c font_metrics.cpp -o font_metrics.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c font_fallback.cpp -o font_fallback.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c string_metrics.cpp -o string_metrics.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c emoji.cpp -o emoji.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c cache_store.cpp -o cache_store.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c init.cpp -o init.o
g++ -std=gnu++11 -I"/usr/share/R/include" -DNDEBUG -I/usr/include/freetype2 -I/usr/include/libpng16 -I/usr/include/freetype2 -I/usr/include/libpng16 -I'/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/cpp11/include'    -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c unix/FontManagerLinux.cpp -o unix/FontManagerLinux.o
g++ -std=gnu++11 -shared -L/usr/lib/R/lib -Wl,-Bsymbolic-functions -Wl,-z,relro -o systemfonts.so caches.o cpp11.o dev_metrics.o font_matching.o font_registry.o ft_cache.o string_shape.o font_metrics.o font_fallback.o string_metrics.o emoji.o cache_store.o init.o unix/FontManagerLinux.o -lfontconfig -lfreetype -L/usr/lib/R/lib -lR
installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-systemfonts/00new/systemfonts/libs
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (systemfonts)
* installing *source* package ‘textshaping’ ...
** package ‘textshaping’ successfully unpacked and MD5 sums checked
** using staged installation
Using PKG_CFLAGS=
Using PKG_LIBS=-lfreetype -lharfbuzz -lfribidi -lpng
Package fribidi was not found in the pkg-config search path.
Perhaps you should add the directory containing `fribidi.pc'
to the PKG_CONFIG_PATH environment variable
No package 'fribidi' found
--------------------------- [ANTICONF] --------------------------------
Configuration failed to find the harfbuzz freetype2 fribidi library. Try installing:
 * deb: libharfbuzz-dev libfribidi-dev (Debian, Ubuntu, etc)
 * rpm: harfbuzz-devel fribidi-devel (Fedora, EPEL)
 * csw: libharfbuzz_dev libfribidi_dev (Solaris)
 * brew: harfbuzz fribidi (OSX)
If harfbuzz freetype2 fribidi is already installed, check that 'pkg-config' is in your
PATH and PKG_CONFIG_PATH contains a harfbuzz freetype2 fribidi.pc file. If pkg-config
is unavailable you can set INCLUDE_DIR and LIB_DIR manually via:
R CMD INSTALL --configure-vars='INCLUDE_DIR=... LIB_DIR=...'
-------------------------- [ERROR MESSAGE] ---------------------------
<stdin>:1:10: fatal error: hb-ft.h: No such file or directory
compilation terminated.
--------------------------------------------------------------------
ERROR: configuration failed for package ‘textshaping’
* removing ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping’
* installing *source* package ‘downlit’ ...
** package ‘downlit’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (downlit)
ERROR: dependency ‘textshaping’ is not available for package ‘ragg’
* removing ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/ragg’
ERROR: dependency ‘ragg’ is not available for package ‘pkgdown’
* removing ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/pkgdown’
[4/10] Installing profvis...

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
also installing the dependency ‘htmlwidgets’

trying URL 'https://cloud.r-project.org/src/contrib/htmlwidgets_1.5.4.tar.gz'
Content type 'application/x-gzip' length 956850 bytes (934 KB)
==================================================
downloaded 934 KB

trying URL 'https://cloud.r-project.org/src/contrib/profvis_0.3.7.tar.gz'
Content type 'application/x-gzip' length 142546 bytes (139 KB)
==================================================
downloaded 139 KB

* installing *source* package ‘htmlwidgets’ ...
** package ‘htmlwidgets’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (htmlwidgets)
* installing *source* package ‘profvis’ ...
** package ‘profvis’ successfully unpacked and MD5 sums checked
** using staged installation
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c pause.c -o pause.o
** libs
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c profvis-init.c -o profvis-init.o
gcc -shared -L/usr/lib/R/lib -Wl,-Bsymbolic-functions -Wl,-z,relro -o profvis.so pause.o profvis-init.o -L/usr/lib/R/lib -lR
installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-profvis/00new/profvis/libs
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
[5/10] Installing rcmdcheck...
** testing if installed package keeps a record of temporary installation path
* DONE (profvis)

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
also installing the dependencies ‘sessioninfo’, ‘xopen’

trying URL 'https://cloud.r-project.org/src/contrib/sessioninfo_1.2.2.tar.gz'
Content type 'application/x-gzip' length 170924 bytes (166 KB)
==================================================
downloaded 166 KB

trying URL 'https://cloud.r-project.org/src/contrib/xopen_1.0.0.tar.gz'
Content type 'application/x-gzip' length 11221 bytes (10 KB)
==================================================
downloaded 10 KB

trying URL 'https://cloud.r-project.org/src/contrib/rcmdcheck_1.4.0.tar.gz'
Content type 'application/x-gzip' length 73522 bytes (71 KB)
==================================================
downloaded 71 KB

* installing *source* package ‘sessioninfo’ ...
** package ‘sessioninfo’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (sessioninfo)
* installing *source* package ‘xopen’ ...
** package ‘xopen’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (xopen)
* installing *source* package ‘rcmdcheck’ ...
** package ‘rcmdcheck’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
[6/10] Installing rversions...
** testing if installed package keeps a record of temporary installation path
* DONE (rcmdcheck)

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
trying URL 'https://cloud.r-project.org/src/contrib/rversions_2.1.2.tar.gz'
Content type 'application/x-gzip' length 42135 bytes (41 KB)
==================================================
downloaded 41 KB

* installing *source* package ‘rversions’ ...
** package ‘rversions’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
[7/10] Installing sessioninfo...
** testing if installed package keeps a record of temporary installation path
* DONE (rversions)

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
trying URL 'https://cloud.r-project.org/src/contrib/sessioninfo_1.2.2.tar.gz'
Content type 'application/x-gzip' length 170924 bytes (166 KB)
==================================================
downloaded 166 KB

* installing *source* package ‘sessioninfo’ ...
** package ‘sessioninfo’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
[8/10] Installing testthat...
** testing if installed package keeps a record of temporary installation path
* DONE (sessioninfo)

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
also installing the dependencies ‘diffobj’, ‘praise’, ‘waldo’

trying URL 'https://cloud.r-project.org/src/contrib/diffobj_0.3.5.tar.gz'
Content type 'application/x-gzip' length 479276 bytes (468 KB)
==================================================
downloaded 468 KB

trying URL 'https://cloud.r-project.org/src/contrib/praise_1.0.0.tar.gz'
Content type 'application/x-gzip' length 6100 bytes
==================================================
downloaded 6100 bytes

trying URL 'https://cloud.r-project.org/src/contrib/waldo_0.4.0.tar.gz'
Content type 'application/x-gzip' length 37556 bytes (36 KB)
==================================================
downloaded 36 KB

trying URL 'https://cloud.r-project.org/src/contrib/testthat_3.1.5.tar.gz'
Content type 'application/x-gzip' length 708287 bytes (691 KB)
==================================================
downloaded 691 KB

* installing *source* package ‘diffobj’ ...
** package ‘diffobj’ successfully unpacked and MD5 sums checked
** using staged installation
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c diff.c -o diff.o
** libs
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c diffobj.c -o diffobj.o
gcc -I"/usr/share/R/include" -DNDEBUG      -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c init.c -o init.o
gcc -shared -L/usr/lib/R/lib -Wl,-Bsymbolic-functions -Wl,-z,relro -o diffobj.so diff.o diffobj.o init.o -L/usr/lib/R/lib -lR
installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-diffobj/00new/diffobj/libs
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (diffobj)
* installing *source* package ‘praise’ ...
** package ‘praise’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (praise)
* installing *source* package ‘waldo’ ...
** package ‘waldo’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (waldo)
* installing *source* package ‘testthat’ ...
** package ‘testthat’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
gcc -I"/usr/share/R/include" -DNDEBUG -I../inst/include -DCOMPILING_TESTTHAT     -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c init.c -o init.o
gcc -I"/usr/share/R/include" -DNDEBUG -I../inst/include -DCOMPILING_TESTTHAT     -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c reassign.c -o reassign.o
g++ -std=gnu++14 -I"/usr/share/R/include" -DNDEBUG -I../inst/include -DCOMPILING_TESTTHAT     -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c test-catch.cpp -o test-catch.o
g++ -std=gnu++14 -I"/usr/share/R/include" -DNDEBUG -I../inst/include -DCOMPILING_TESTTHAT     -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c test-example.cpp -o test-example.o
g++ -std=gnu++14 -I"/usr/share/R/include" -DNDEBUG -I../inst/include -DCOMPILING_TESTTHAT     -fpic  -g -O2 -fdebug-prefix-map=/build/r-base-AINzno/r-base-4.2.2=. -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2  -c test-runner.cpp -o test-runner.o
g++ -std=gnu++14 -shared -L/usr/lib/R/lib -Wl,-Bsymbolic-functions -Wl,-z,relro -o testthat.so init.o reassign.o test-catch.o test-example.o test-runner.o -L/usr/lib/R/lib -lR
installing to /home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/00LOCK-testthat/00new/testthat/libs
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
*** copying figures
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (testthat)
[9/10] Installing urlchecker...

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
trying URL 'https://cloud.r-project.org/src/contrib/urlchecker_1.0.1.tar.gz'
Content type 'application/x-gzip' length 13340 bytes (13 KB)
==================================================
downloaded 13 KB

* installing *source* package ‘urlchecker’ ...
** package ‘urlchecker’ successfully unpacked and MD5 sums checked
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
** help
*** installing help indices
** building package indices
** testing if installed package can be loaded from temporary location
** testing if installed package can be loaded from final location
[10/10] Installing devtools...
** testing if installed package keeps a record of temporary installation path
* DONE (urlchecker)

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’
Installing package into ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2’
(as ‘lib’ is unspecified)
also installing the dependencies ‘textshaping’, ‘ragg’, ‘pkgdown’

trying URL 'https://cloud.r-project.org/src/contrib/textshaping_0.3.6.tar.gz'
Content type 'application/x-gzip' length 35722 bytes (34 KB)
==================================================
downloaded 34 KB

trying URL 'https://cloud.r-project.org/src/contrib/ragg_1.2.4.tar.gz'
Content type 'application/x-gzip' length 427579 bytes (417 KB)
==================================================
downloaded 417 KB

trying URL 'https://cloud.r-project.org/src/contrib/pkgdown_2.0.6.tar.gz'
Content type 'application/x-gzip' length 871371 bytes (850 KB)
==================================================
downloaded 850 KB

trying URL 'https://cloud.r-project.org/src/contrib/devtools_2.4.5.tar.gz'
Content type 'application/x-gzip' length 374718 bytes (365 KB)
==================================================
downloaded 365 KB

Using PKG_CFLAGS=
Using PKG_LIBS=-lfreetype -lharfbuzz -lfribidi -lpng
* installing *source* package ‘textshaping’ ...
** package ‘textshaping’ successfully unpacked and MD5 sums checked
** using staged installation
Package fribidi was not found in the pkg-config search path.
Perhaps you should add the directory containing `fribidi.pc'
to the PKG_CONFIG_PATH environment variable
No package 'fribidi' found
--------------------------- [ANTICONF] --------------------------------
Configuration failed to find the harfbuzz freetype2 fribidi library. Try installing:
 * deb: libharfbuzz-dev libfribidi-dev (Debian, Ubuntu, etc)
 * rpm: harfbuzz-devel fribidi-devel (Fedora, EPEL)
 * csw: libharfbuzz_dev libfribidi_dev (Solaris)
 * brew: harfbuzz fribidi (OSX)
If harfbuzz freetype2 fribidi is already installed, check that 'pkg-config' is in your
PATH and PKG_CONFIG_PATH contains a harfbuzz freetype2 fribidi.pc file. If pkg-config
is unavailable you can set INCLUDE_DIR and LIB_DIR manually via:
R CMD INSTALL --configure-vars='INCLUDE_DIR=... LIB_DIR=...'
-------------------------- [ERROR MESSAGE] ---------------------------
<stdin>:1:10: fatal error: hb-ft.h: No such file or directory
compilation terminated.
--------------------------------------------------------------------
ERROR: configuration failed for package ‘textshaping’
* removing ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/textshaping’
ERROR: dependency ‘textshaping’ is not available for package ‘ragg’
* removing ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/ragg’
ERROR: dependency ‘ragg’ is not available for package ‘pkgdown’
* removing ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/pkgdown’
ERROR: dependency ‘pkgdown’ is not available for package ‘devtools’
* removing ‘/home/dhankar/R/x86_64-pc-linux-gnu-library/4.2/devtools’

The downloaded source packages are in
	‘/tmp/RtmpUdFXzQ/downloaded_packages’


✔ Package 'devtools' successfully installed.
Warning messages:
1: In utils::install.packages("pkgdown", repos = "https://cloud.r-project.org") :
  installation of package ‘textshaping’ had non-zero exit status
2: In utils::install.packages("pkgdown", repos = "https://cloud.r-project.org") :
  installation of package ‘ragg’ had non-zero exit status
3: In utils::install.packages("pkgdown", repos = "https://cloud.r-project.org") :
  installation of package ‘pkgdown’ had non-zero exit status
4: In utils::install.packages("devtools", repos = "https://cloud.r-project.org") :
  installation of package ‘textshaping’ had non-zero exit status
5: In utils::install.packages("devtools", repos = "https://cloud.r-project.org") :
  installation of package ‘ragg’ had non-zero exit status
6: In utils::install.packages("devtools", repos = "https://cloud.r-project.org") :
  installation of package ‘pkgdown’ had non-zero exit status
7: In utils::install.packages("devtools", repos = "https://cloud.r-project.org") :
  installation of package ‘devtools’ had non-zero exit status
```  