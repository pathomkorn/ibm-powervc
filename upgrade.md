# IBM PowerVC Upgrade Step

* Install Red Hat Enterprise Linux 7.1
* Install IBM PowerVC 1.2.3.0
  * Back up files: /etc/sudoers, /etc/security/limits.conf, /etc/sysctl.conf
  * ```export HOST_INTERFACE=eno16780032```
  * ```yum install pyserial-2.6-5.el7.noarch.rpm python-fpconst-0.7.3-12.el7.noarch.rpm python-pyasn1-modules-0.1.6-2.el7.noarch.rpm python-twisted-core-12.2.0-4.el7.x86_64.rpm python-twisted-web-12.1.0-4.el7.x86_64.rpm python-zope-interface-4.0.5-4.el7.x86_64.rpm SOAPpy-0.11.6-17.el7.noarch.rpm```
  * ```./install```
* Upgrade IBM PowerVC 1.2.3.2
  * ```./update```
  * Configure YUM exclude list + python2-cryptography python2-oauthlib
* Upgrade Red Hat Enterprise Linux 7.2/7.3/7.4
* Upgrade IBM PowerVC 1.3.1.0
* Upgrade IBM PowerVC 1.3.1.2
* Upgrade IBM PowerVC 1.3.3.0
* Upgrade IBM PowerVC 1.3.3.1
