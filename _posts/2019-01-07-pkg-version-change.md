---
layout: post
title:  pkg version change 2019-01-07
date:   2019-01-07 23:59:59
category: pkg
---

    --- /var/db/pkg/version/2019-01-06	2019-01-07 00:55:00.820365000 +0900
    +++ /var/db/pkg/version/2019-01-07	2019-01-08 00:55:01.605904000 +0900
    @@ -1,150 +1,142 @@
    -apache24-2.4.29                    =
    -apr-1.6.3.1.6.1                    =
    -asciidoc-8.6.10                    =
    -asterisk13-13.17.1                 <
    -autoconf-2.69_1                    =
    +apache24-2.4.37                    =
    +apr-1.6.5.1.6.1_1                  =
    +autoconf-2.69_2                    =
     autoconf-wrapper-20131203          =
    -automake-1.15.1                    =
    -automake-wrapper-20131203          =
    -bash-4.4.12_3                      =
    -binutils-2.28,1                    <
    -bison-3.0.4,1                      =
    -boehm-gc-7.6.0                     <
    -c-ares-1.12.0_2                    =
    -ca_root_nss-3.36                   >
    -cmake-3.10.1_1                     <
    -compat7x-amd64-7.4.704000.201310.1 =
    -curl-7.58.0                        <
    +automake-1.16.1_1                  =
    +bash-4.4.23_1                      =
    +binutils-2.30_7,1                  =
    +bison-3.2.2,1                      =
    +c-ares-1.14.0_2                    =
    +ca_root_nss-3.41                   =
    +cmake-3.13.2                       =
    +curl-7.62.0                        <
     cvsps-2.1_2                        =
    -cyrus-sasl-2.1.26_13               =
    +cyrus-sasl-2.1.27                  =
     dahdi-2.4.0rc5_7                   =
    -db5-5.3.28_6                       =
    +db5-5.3.28_7                       =
     dialog4ports-0.1.6                 =
    -docbook-1.5                        =
    -docbook-sgml-4.5_1                 =
    -docbook-xml-5.0_3                  =
    -docbook-xsl-1.76.1_3               <
     dropbox-api-command-2.13,1         =
    -e2fsprogs-libuuid-1.44.0           >
    -easy-rsa-3.0.1_1                   =
    -expat-2.2.5                        =
    -ezjail-3.4.2                       =
    -fftw3-3.3.6.p2_2                   <
    -fontconfig-2.12.1,1                =
    -freetds-1.00.59,1                  <
    -freetype2-2.8_1                    =
    -gamin-0.1.10_9                     =
    -gcc-6                              =
    +e2fsprogs-libuuid-1.44.5           =
    +easy-rsa-3.0.5_1                   =
    +expat-2.2.6_1                      =
    +ezjail-3.4.2_1                     =
    +fftw3-3.3.8_3                      =
    +fontconfig-2.12.6,1                =
    +freetds-1.00.109,1                 =
    +freetype2-2.9.1                    =
    +gamin-0.1.10_10                    =
    +gcc-8_3                            =
     gcc-ecj-4.5                        =
    -gcc5-5.5.0_1                       =
    -gcc6-6.4.0_3                       =
    -gdbm-1.13_1                        =
    +gcc5-5.5.0_6                       =
    +gcc6-6.5.0_3                       =
    +gcc8-8.2.0_4                       =
    +gdbm-1.18.1                        =
     getopt-1.1.6                       =
     gettext-0.19.8.1                   =
    -gettext-runtime-0.19.8.1_1         =
    -gettext-tools-0.19.8.1             =
    -git-2.15.1                         <
    -glib-2.50.3_1,1                    =
    -gmake-4.2.1_1                      =
    -gmp-6.1.2                          =
    -gnupg-2.2.4                        =
    -gnutls-3.5.16                      <
    -gpgme-1.9.0_1                      <
    +gettext-runtime-0.19.8.1_2         =
    +gettext-tools-0.19.8.1_1           =
    +git-2.20.1                         =
    +glib-2.56.3_2,1                    =
    +gmake-4.2.1_3                      =
    +gmp-6.1.2_1                        =
    +gnupg-2.2.12                       =
    +gnutls-3.6.5                       <
     gsm-1.0.13_2                       =
    -gtar-1.29                          =
    -help2man-1.47.5                    =
    -icu-60.2_1,1                       =
    -iksemel-1.4_7                      =
    +gtar-1.30_1                        =
    +help2man-1.47.8_1                  =
    +icu-63.1_1,1                       =
    +iksemel-1.4_8                      =
     indexinfo-0.3.1                    =
    +intltool-0.51.0_1                  =
     iso8879-1986_3                     =
    -ja-groff-1.18.1_17                 =
    +ja-groff-1.18.1_18                 =
     ja-less-382.262.03.01              =
     ja-man-1.1j_9                      =
     ja-man-doc-5.4.20050911_3          =
    -jansson-2.10                       =
    +jansson-2.12                       =
     jbigkit-2.1_1                      =
    -jpeg-turbo-1.5.3                   =
    -jsoncpp-1.8.1_2                    =
    -libarchive-3.3.2,1                 =
    -libassuan-2.5.1                    =
    -libatomic_ops-7.6.0_1              =
    +jpeg-turbo-2.0.1                   =
    +jsoncpp-1.8.1_5                    =
    +libarchive-3.3.3,1                 =
    +libassuan-2.5.1_1                  <
     libedit-3.1.20170329_2,1           =
    -libevent-2.1.8_1                   =
    +libevent-2.1.8_2                   =
     libexecinfo-1.1_3                  ?
    -libffi-3.2.1_2                     =
    -libfpx-1.3.1.4_1                   <
    -libgcrypt-1.8.2                    =
    -libgpg-error-1.27                  =
    +libffi-3.2.1_3                     =
    +libfpx-1.3.1.10                    =
    +libgcrypt-1.8.4_1                  =
    +libgpg-error-1.33                  =
     libiconv-1.14_11                   =
    -libidn-1.33_1                      =
    -libidn2-2.0.4                      =
    -libksba-1.3.5                      =
    +libidn2-2.0.5_1                    <
    +libksba-1.3.5_1                    =
     liblqr-1-0.4.2                     =
     libltdl-2.4.6                      =
    -liblz4-1.8.0,1                     <
    -libnghttp2-1.29.0                  =
    +liblz4-1.8.3,1                     =
    +libnghttp2-1.35.1                  =
     libogg-1.3.3,4                     =
    -libpaper-1.1.24.4                  =
    -libpri-1.5.0                       =
    -libslang2-2.3.1_1                  =
    -libtasn1-4.12                      <
    -libtool-2.4.6                      =
    -libunistring-0.9.8                 =
    -libunwind-20170113_1               <
    -libuv-1.18.0                       <
    -libvorbis-1.3.6,3                  >
    -libxml2-2.9.7                      =
    -libxslt-1.1.29_1                   =
    -libyaml-0.1.6_2                    =
    -lsof-4.90.q,8                      =
    +libpri-1.6.0                       =
    +libslang2-2.3.2_1                  =
    +libsrtp2-2.2.0                     =
    +libtasn1-4.13_1                    =
    +libtool-2.4.6_1                    =
    +libunistring-0.9.10_1              =
    +libunwind-20170615                 =
    +libuv-1.24.1                       =
    +libvorbis-1.3.6,3                  =
    +libxml2-2.9.7                      <
    +libxslt-1.1.32                     =
    +libyaml-0.2.1                      =
    +lsof-4.92.b_1,8                    =
     lua51-5.1.5_9                      =
    +lua52-5.2.4                        =
     lv-4.51_3                          =
     lzo2-2.10_1                        =
    -m4-1.4.18,1                        =
    -mime-support-3.60                  =
    +m4-1.4.18_1,1                      =
    +mime-support-3.61                  =
     mkfile-1.1.3_1                     =
    -mpc-1.0.3                          =
    -mpfr-3.1.6                         =
    -mpg123-1.25.8                      =
    -mysql56-client-5.6.39              =
    -net-snmp-5.7.3_17                  =
    -nettle-3.4                         =
    +mpc-1.1.0_2                        =
    +mpfr-4.0.1_2                       =
    +mpg123-1.25.10                     =
    +mysql56-client-5.6.42_1            =
    +net-snmp-5.7.3_19                  =
    +nettle-3.4.1_1                     =
     newt-0.52.20                       =
    -nfdump-1.6.13_1                    <
    -nmap-7.40_1                        <
    -node-9.3.0                         <
    -npth-1.5                           =
    +nfdump-1.6.17                      =
    +nmap-7.70                          =
    +node-11.6.0                        =
    +npth-1.6                           =
     openr2-1.3.3                       =
    -openvpn-2.4.4_1                    >
    -p11-kit-0.23.9                     =
    +openvpn-2.4.6_3                    =
    +p11-kit-0.23.14                    =
     p5-Algorithm-C3-0.10_1             =
     p5-Authen-NTLM-1.09_1              =
     p5-Authen-SASL-2.16_1              =
    -p5-B-Hooks-EndOfScope-0.21         =
    +p5-B-Hooks-EndOfScope-0.24         =
     p5-BerkeleyDB-0.55_1               =
    +p5-CGI-4.40                        =
     p5-Class-Accessor-0.51             =
     p5-Class-Accessor-Lite-0.08        =
    -p5-Class-C3-0.33                   =
    +p5-Class-C3-0.34                   =
     p5-Class-Data-Inheritable-0.08_1   =
     p5-Class-Inspector-1.32            =
    -p5-Class-Load-0.24                 =
    +p5-Class-Load-0.25                 =
     p5-Class-Method-Modifiers-2.12     =
     p5-Class-Singleton-1.5_1           =
     p5-Data-OptList-0.110              =
    -p5-DateTime-1.45                   =
    +p5-DateTime-1.50                   =
     p5-DateTime-Format-Strptime-1.75,1 =
    -p5-DateTime-Locale-1.17            =
    -p5-DateTime-TimeZone-2.13,1        =
    +p5-DateTime-Locale-1.23            =
    +p5-DateTime-TimeZone-2.21,1        =
     p5-Devel-StackTrace-2.03           =
     p5-Digest-HMAC-1.03_1              =
     p5-Dist-CheckConflicts-0.11_1      =
     p5-Encode-Locale-1.05              =
    -p5-Error-0.17025                   =
    +p5-Error-0.17027                   =
     p5-Eval-Closure-0.14               =
     p5-Exception-Class-1.44            =
    -p5-Exporter-Tiny-1.000000          =
    +p5-Exporter-Tiny-1.002001          =
     p5-File-Listing-6.04_1             =
    -p5-File-ShareDir-1.104             =
    +p5-File-ShareDir-1.116             =
     p5-Furl-3.07                       =
     p5-GSSAPI-0.28_1                   =
     p5-HTML-Parser-3.72                =
    @@ -152,172 +144,147 @@
     p5-HTTP-Cookies-6.04               =
     p5-HTTP-Daemon-6.01_1              =
     p5-HTTP-Date-6.02_1                =
    -p5-HTTP-Message-6.14               =
    +p5-HTTP-Message-6.18               =
     p5-HTTP-Negotiate-6.01_1           =
     p5-HTTP-Parser-XS-0.17             =
     p5-IO-HTML-1.001_1                 =
    -p5-IO-Multiplex-1.13_1             =
    +p5-IO-Multiplex-1.16               =
     p5-IO-Socket-INET6-2.72_1          =
     p5-IO-Socket-IP-0.39               =
    -p5-IO-Socket-SSL-2.051             =
    -p5-JSON-2.90_1                     <
    +p5-IO-Socket-SSL-2.060             =
    +p5-JSON-2.97.001                   =
     p5-JSON-XS-3.04                    =
     p5-LWP-MediaTypes-6.02_1           =
     p5-LWP-Protocol-https-6.07_1       =
    -p5-List-AllUtils-0.14              =
     p5-List-MoreUtils-0.428            =
     p5-List-MoreUtils-XS-0.428         =
    -p5-List-SomeUtils-0.56             =
    -p5-List-SomeUtils-XS-0.56          =
    -p5-List-UtilsBy-0.10               =
     p5-Locale-gettext-1.07             =
     p5-MRO-Compat-0.13                 =
     p5-Module-Build-0.4224             =
     p5-Module-Implementation-0.09_1    =
     p5-Module-Runtime-0.016            =
    -p5-Mozilla-CA-20160104             =
    -p5-Net-DNS-1.14,1                  =
    -p5-Net-HTTP-6.17                   =
    +p5-Mozilla-CA-20180117             =
    +p5-Net-DNS-1.19,1                  =
    +p5-Net-HTTP-6.18                   =
     p5-Net-OAuth-0.28_1                =
    -p5-Net-SMTP-SSL-1.04               =
    -p5-Net-SSLeay-1.82                 <
    +p5-Net-SMTP-SSL-1.04               ?
    +p5-Net-SSLeay-1.85                 =
     p5-Net-Server-2.009                =
    -p5-NetAddr-IP-4.078                =
    +p5-NetAddr-IP-4.079                =
     p5-Package-DeprecationManager-0.17_1 =
     p5-Package-Stash-0.37_1            =
     p5-Package-Stash-XS-0.28_2         =
     p5-Params-Util-1.07_2              =
     p5-Params-Validate-1.29            =
    -p5-Params-ValidationCompiler-0.26  =
    +p5-Params-ValidationCompiler-0.30  =
     p5-Parse-Syslog-1.10_1             =
     p5-Path-Class-0.37                 =
     p5-Role-Tiny-2.000006              =
    -p5-Scalar-List-Utils-1.48,1        =
    -p5-Socket-2.024                    <
    -p5-Socket6-0.28                    =
    -p5-Specio-0.42                     =
    -p5-String-Random-0.29,1            =
    +p5-Scalar-List-Utils-1.50,1        =
    +p5-Socket-2.027                    =
    +p5-Socket6-0.29                    =
    +p5-Specio-0.43                     =
    +p5-String-Random-0.30,1            =
     p5-Sub-Exporter-0.987_1            =
     p5-Sub-Exporter-Progressive-0.001013 =
     p5-Sub-Identify-0.14               =
     p5-Sub-Install-0.928_1             =
     p5-Sub-Name-0.21,1                 =
    -p5-Sub-Quote-2.004000              =
    -p5-Try-Tiny-0.28                   =
    +p5-Sub-Quote-2.005001              =
    +p5-Try-Tiny-0.30                   =
     p5-Types-Serialiser-1.0_1          =
    -p5-URI-1.72                        <
    +p5-URI-1.74                        =
     p5-Variable-Magic-0.62             =
     p5-WWW-RobotRules-6.02_1           =
     p5-WebService-Dropbox-2.07         =
    +p5-XML-Parser-2.44                 =
     p5-common-sense-3.74               =
    -p5-libwww-6.31                     =
    +p5-libwww-6.36                     =
     p5-namespace-autoclean-0.28        =
     p5-namespace-clean-0.27            =
    -password-store-1.7.1_1             <
    -pcre-8.40_1                        =
    -pefs-kmod-2017.06.20               =
    -perl5-5.24.3                       =
    -phantomjs-2.1.1_7                  =
    -pinentry-1.0.0_3                   <
    -pinentry-tty-1.0.0                 <
    -pjsip-2.7.1                        =
    -pkg-1.10.3_1                       <
    +password-store-1.7.3               =
    +pcre-8.42_1                        =
    +pefs-kmod-2018.11.26               =
    +perl5-5.28.1                       =
    +phantomjs-2.1.1_12                 =
    +pinentry-1.1.0_3                   =
    +pinentry-tty-1.1.0                 =
    +pjsip-2.8                          =
    +pkg-1.10.5_5                       =
     pkg_tree-1.1_4                     =
    -pkgconf-1.3.10,1                   <
    -png-1.6.34                         =
    +pkgconf-1.5.4,1                    =
    +png-1.6.36                         =
     popt-1.16_2                        =
    -portaudio-19.20140130_6            =
    -portmaster-3.18_4                  <
    -portupgrade-2.4.15,2               =
    -postfix-3.2.5,1                    =
    -postgresql96-client-9.6.8          >
    -postgresql96-server-9.6.8          >
    -postgrey-1.37                      =
    +portaudio-19.6.0,1                 =
    +portmaster-3.19_18                 =
    +portupgrade-2.4.16,2               =
    +postfix-3.3.2_1,1                  =
    +postgresql96-client-9.6.11_2       =
    +postgresql96-server-9.6.11_2       =
    +postgrey-1.37_3                    =
     procmail-3.22_10                   =
    -pwgen-2.07,2                       =
    -py27-Babel-2.5.1                   =
    -py27-Jinja2-2.10                   =
    -py27-MarkupSafe-1.0                =
    -py27-acme-0.20.0,1                 <
    -py27-alabaster-0.7.6               =
    +pwgen-2.08,2                       =
    +py27-acme-0.29.1,1                 =
     py27-asn1crypto-0.22.0             =
    -py27-certbot-0.20.0,1              <
    -py27-certifi-2017.11.5             <
    -py27-cffi-1.7.0                    <
    +py27-certbot-0.29.1_2,1            =
    +py27-certifi-2018.11.29            =
    +py27-cffi-1.11.5                   =
     py27-chardet-3.0.4                 =
    -py27-configargparse-0.12.0         =
    +py27-configargparse-0.13.0         =
     py27-configobj-5.0.6_1             =
    -py27-cryptography-2.0.3            <
    -py27-dnspython-1.15.0              =
    -py27-docutils-0.14_1               =
    +py27-cryptography-2.3              =
     py27-enum34-1.1.6                  =
    -py27-funcsigs-1.0.2                =
    -py27-idna-2.5                      =
    -py27-imagesize-0.7.1               =
    -py27-ipaddress-1.0.19              =
    -py27-mock-2.0.0                    =
    -py27-ndg_httpsclient-0.4.3         <
    -py27-openssl-17.3.0                <
    +py27-idna-2.7                      =
    +py27-ipaddress-1.0.22              =
    +py27-josepy-1.1.0                  =
    +py27-openssl-18.0.0                =
     py27-parsedatetime-2.4_1           =
    -py27-pbr-3.1.1                     =
    -py27-pip-9.0.1                     =
    -py27-psutil-5.4.2                  <
    -py27-pyasn1-0.3.7                  <
    -py27-pycparser-2.10                =
    -py27-pygments-2.2.0                =
    -py27-pyrfc3339-1.0                 =
    +py27-pycparser-2.18                =
    +py27-pyrfc3339-1.1                 =
     py27-pysocks-1.6.8                 =
    -py27-pystemmer-1.3.0_1             =
    -py27-python2-pythondialog-3.4.0_1  =
    -py27-pytz-2017.3,1                 =
    -py27-requests-2.18.1_1             =
    -py27-setuptools-36.5.0             <
    -py27-six-1.11.0                    =
    -py27-snowballstemmer-1.2.0_1       =
    -py27-sphinx-1.4.8_2,1              <
    -py27-sphinx_rtd_theme-0.2.4        =
    -py27-sqlite3-2.7.14_7              =
    -py27-urllib3-1.22                  =
    -py27-werkzeug-0.13                 <
    +py27-pytz-2018.7,1                 =
    +py27-requests-2.18.4_1             =
    +py27-requests-toolbelt-0.8.0       =
    +py27-setuptools-40.6.2             =
    +py27-six-1.12.0                    =
    +py27-sqlite3-2.7.15_7              =
    +py27-urllib3-1.22,1                =
     py27-zope.component-4.2.2          =
     py27-zope.event-4.1.0              =
    -py27-zope.interface-4.1.3          =
    +py27-zope.interface-4.6.0          =
     python2-2_3                        =
    -python27-2.7.14_1                  =
    +python27-2.7.15                    =
     radiusclient-0.5.6_3               =
    -readline-7.0.3_1                   =
    +readline-7.0.5                     =
     rhash-1.3.5                        =
    -ruby-2.4.3,1                       =
    -ruby22-2.2.9,1                     ?
    -ruby22-bdb-0.6.6_5                 ?
    -ruby23-bdb-0.6.6_5                 ?
    +rrdtool-1.7.0_2                    =
    +ruby-2.4.5_1,1                     =
     ruby24-bdb-0.6.6_5                 =
    -ruby24-gems-2.6.14                 <
    +ruby24-gems-2.7.8                  =
     rubygem-file-tail-1.2.0            =
    -rubygem-tins-1.16.3                =
    +rubygem-tins-1.20.2                =
     scponly-4.8.20110526_2             =
    -screen-4.6.2                       =
    -sdocbook-xml-1.1_2,2               =
    +screen-4.6.2_1                     =
     spandsp-0.0.6                      =
     speex-1.2.0,1                      =
     speexdsp-1.2.r3_1                  =
     sqlite-2.8.17_4                    =
    -sqlite3-3.21.0_1                   =
    -squid-3.5.27_3                     >
    -strongswan-5.6.2_1                 >
    -sudo-1.8.21p2_1                    <
    +sqlite3-3.26.0                     =
    +squid-4.4_1                        =
    +strongswan-5.7.1                   =
    +sudo-1.8.26                        =
     sysconftool-0.17                   =
    -tiff-4.0.9_1                       =
    +tiff-4.0.10                        =
     tpm-emulator-0.7.4_2               =
     tree-1.7.0                         =
    -tripwire-2.4.3.6                   =
    +tripwire-2.4.3.7                   =
     trousers-0.3.14_2                  =
    -unixODBC-2.3.4                     =
    +unixODBC-2.3.7                     =
     unzip-6.0_7                        =
     urlview-0.9.20131021_1             =
    -v8-3.18.5_4                        =
    +v8-3.18.5_7                        =
     vim-lite-8.0.1427                  ?
     xmlcatmgr-2.2_2                    =
     xmlcharent-0.3_2                   =
     zip-3.0_1                          =
    -zsh-5.4.2_1                        =
    +zsh-5.6.2_1                        =
