## alban.andrieu.cpp

[![Travis CI](http://img.shields.io/travis/AlbanAndrieu/ansible-cpp.svg?style=flat)](http://travis-ci.org/AlbanAndrieu/ansible-cpp) [![Branch](http://img.shields.io/github/tag/AlbanAndrieu/ansible-cpp.svg?style=flat-square)](https://github.com/AlbanAndrieu/ansible-cpp/tree/master) [![Donate](https://img.shields.io/gratipay/AlbanAndrieu.svg?style=flat)](https://www.gratipay.com/AlbanAndrieu)  [![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Ensures that the basic cpp requirements are properly installed (using `apt`) and configured


### Role dependencies

- `alban.andrieu.cmake`

### Role variables

List of default variables available in the inventory:

```yaml
        cpp_enabled: yes                       # Enable module
    
    gcc_version: "4:4.6.3-1ubuntu5"
    #gcc_version: "4:4.8.2-1ubuntu6"
    cppunit_version: "1.12-1"
    #cppunit_version: "1.13-0"
    boost_version: "1.48"
    #boost_version: "1.54"
```


### Detailed usage guide

Describe how to use in more detail...


### Authors and license

`alban.andrieu.cpp` role was written by:
- [alban.andrieu](fr.linkedin.com/in/nabla/) | [e-mail](mailto:alban.andrieu@free.fr) | [Twitter](https://twitter.com/AlbanAndrieu) | [GitHub](https://github.com/AlbanAndrieu)
- License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-cpp/issues)!

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
