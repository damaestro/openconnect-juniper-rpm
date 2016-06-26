# openconnect-juniper-rpm
Openconnect source rpm tree with juniper configured as default for use with unmodified network manager openconnect plugin

## RPM Install Instructions
This is the [tito](https://github.com/dgoodwin/tito) managed source for [copr](https://fedorahosted.org/copr/) builds. To actually use these packages:

```
dnf copr enable jsteffan/openconnect-juniper
dnf install openconnect
```

Please note that there might be a newer upstream package update that will be newer than what is in this repo. Always be sure you have the right version installed. For more information see the [copr repo for openconnect-juniper](https://copr.fedorainfracloud.org/coprs/jsteffan/openconnect-juniper/).
