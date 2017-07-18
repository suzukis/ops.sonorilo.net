---
layout: post
title:  pkg version change 2017-07-18
date:   2017-07-18 23:59:59
category: pkg
---

    --- /var/db/pkg/version/2017-07-17	2017-07-18 00:55:01.052424736 +0900
    +++ /var/db/pkg/version/2017-07-18	2017-07-19 00:55:00.215482951 +0900
    @@ -14,6 +14,7 @@
     ca_root_nss-3.30.2                 =
     cmake-3.8.0                        =
     cmake-modules-3.8.0                =
    +compat7x-amd64-7.4.704000.201310.1 =
     curl-7.54.0                        =
     cvsps-2.1_2                        =
     cyrus-sasl-2.1.26_12               =
    @@ -233,10 +234,12 @@
     py27-Babel-2.3.4                   =
     py27-Jinja2-2.9.5                  =
     py27-MarkupSafe-1.0                =
    -py27-acme-0.13.0_1,1               <
    +py27-acme-0.15.0_1,1               >
     py27-alabaster-0.7.6               =
    -py27-certbot-0.13.0_1,1            <
    +py27-certbot-0.15.0_1,1            >
    +py27-certifi-2017.4.17             =
     py27-cffi-1.7.0                    =
    +py27-chardet-3.0.3                 >
     py27-configargparse-0.12.0         =
     py27-configobj-5.0.6_1             =
     py27-cryptography-1.7.2            =
    @@ -244,7 +247,7 @@
     py27-docutils-0.13.1               =
     py27-enum34-1.1.6                  =
     py27-funcsigs-1.0.2                =
    -py27-idna-2.0                      =
    +py27-idna-2.5                      >
     py27-imagesize-0.7.1               =
     py27-ipaddress-1.0.18              =
     py27-mock-2.0.0                    =
    @@ -258,21 +261,23 @@
     py27-pycparser-2.10                =
     py27-pygments-2.2.0                =
     py27-pyrfc3339-1.0                 =
    +py27-pysocks-1.6.7                 =
     py27-pystemmer-1.3.0_1             =
     py27-python2-pythondialog-3.4.0    =
     py27-pytz-2016.10,1                =
    -py27-requests-2.11.1               =
    -py27-setuptools-32.1.0_1           =
    +py27-requests-2.18.1               >
    +py27-setuptools-36.0.1             >
     py27-six-1.10.0                    =
     py27-snowballstemmer-1.2.0_1       =
     py27-sphinx-1.4.8,1                =
     py27-sphinx_rtd_theme-0.2.4        =
    +py27-urllib3-1.21.1                =
     py27-werkzeug-0.12.2               =
     py27-zope.component-4.2.2          =
     py27-zope.event-4.1.0              =
     py27-zope.interface-4.1.3          =
     python2-2_3                        =
    -python27-2.7.13_3                  =
    +python27-2.7.13_6                  >
     radiusclient-0.5.6_3               =
     readline-6.3.8_1                   =
     rhash-1.3.4                        =
