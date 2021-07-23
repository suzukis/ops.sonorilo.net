---
layout: post
title:  pkg version change 2021-07-23
date:   2021-07-23 23:59:59
category: pkg
---

    --- /var/db/pkg/version/2021-07-22	2021-07-23 01:21:00.077940000 +0900
    +++ /var/db/pkg/version/2021-07-23	2021-07-24 01:21:00.138175000 +0900
    @@ -2,6 +2,8 @@
     apr-1.7.0.1.6.1_1                  =
     bash-5.1.4                         <
     bash-completion-2.11,2             =
    +bind-tools-9.16.18                 =
    +bind916-9.16.18                    =
     brotli-1.0.9,1                     =
     c-ares-1.17.1                      =
     ca_root_nss-3.58                   <
    @@ -10,6 +12,7 @@
     db5-5.3.28_7                       =
     easy-rsa-3.0.8                     =
     expat-2.2.10                       <
    +fstrm-0.6.1                        =
     gdbm-1.18.1_1                      <
     gettext-runtime-0.21               =
     git-2.30.1                         <
    @@ -18,19 +21,21 @@
     gmp-6.2.1                          =
     gnupg-2.2.26                       <
     gnutls-3.6.15                      =
    -icu-68.2,1                         =
    +icu-68.2,1                         <
     indexinfo-0.3.1                    =
     iperf-2.0.14a_3                    <
    -iperf3-3.9                         =
    +iperf3-3.9                         <
     jansson-2.13.1                     =
    -libassuan-2.5.4                    =
    +json-c-0.15_1                      =
    +libassuan-2.5.4                    <
     libedit-3.1.20191231,1             <
    +libevent-2.1.12                    =
     libffi-3.3_1                       =
     libgcrypt-1.8.7                    <
     libgpg-error-1.41                  <
     libiconv-1.16                      =
    -libidn2-2.3.0_1                    =
    -libksba-1.5.0                      =
    +libidn2-2.3.0_1                    <
    +libksba-1.5.0                      <
     liblz4-1.9.3,1                     =
     libnghttp2-1.42.0                  <
     libtasn1-4.16.0                    <
    @@ -38,27 +43,29 @@
     libunwind-20200331_1               <
     libuv-1.41.0                       =
     libxml2-2.9.10_2                   <
    -libxslt-1.1.34_1                   =
    +libxslt-1.1.34_1                   <
     libyaml-0.2.5                      =
     llvm10-10.0.1_5                    =
    +lmdb-0.9.28,1                      =
     lua52-5.2.4                        =
     lv-4.51.20200728                   =
     lzo2-2.10_1                        =
    -nettle-3.7.2_1                     =
    +mpdecimal-2.5.1                    =
    +nettle-3.7.2_1                     <
     nginx-1.18.0_45,2                  <
    -nmap-7.91                          =
    +nmap-7.91                          <
     node-15.10.0                       <
     npth-1.6                           =
     openvpn-2.5.1                      <
     p11-kit-0.23.22                    <
     p5-Authen-SASL-2.16_1              =
    -p5-CGI-4.51                        =
    +p5-CGI-4.51                        <
     p5-Clone-0.45                      =
    -p5-Digest-HMAC-1.03_1              =
    +p5-Digest-HMAC-1.03_1              <
     p5-Encode-Locale-1.05              =
     p5-Error-0.17029                   =
     p5-GSSAPI-0.28_1                   =
    -p5-HTML-Parser-3.75                =
    +p5-HTML-Parser-3.75                <
     p5-HTML-Tagset-3.20_1              =
     p5-HTTP-Date-6.05                  =
     p5-HTTP-Message-6.26               <
    @@ -67,14 +74,14 @@
     p5-IO-Socket-SSL-2.068             <
     p5-LWP-MediaTypes-6.04             =
     p5-Mozilla-CA-20200520             =
    -p5-Net-SSLeay-1.88                 =
    +p5-Net-SSLeay-1.88                 <
     p5-Socket6-0.29                    =
     p5-Term-ReadKey-2.38_1             =
     p5-TimeDate-2.33,1                 =
     p5-URI-5.05                        <
     p5-subversion-1.14.1               =
     pcre-8.44                          =
    -pefs-kmod-2018.11.26               =
    +pefs-kmod-2018.11.26               <
     perl5-5.32.1_1                     =
     pinentry-1.1.0_7                   <
     pinentry-tty-1.1.0                 <
    @@ -82,7 +89,12 @@
     pkgconf-1.7.3,1                    <
     postgresql13-client-13.3           =
     postgresql13-server-13.3_1         =
    +protobuf-3.14.0,1                  =
    +protobuf-c-1.4.0                   =
    +py38-ply-3.11                      =
    +py38-setuptools-57.0.0             =
     python37-3.7.9_1                   <
    +python38-3.8.10                    =
     readline-8.0.4                     <
     ruby-2.7.2_1,1                     <
     ruby27-gems-3.0.8                  =
