Example JPackage Maven project
==============================

Automatically built via the [GitHub Actions CI/CD](https://github.com/mjw99/hellojpackage/actions)

Example building locally for Debian style system:
```
mvn clean package && sudo dpkg -i ./target/dist/*.deb && /opt/hellojpackage/bin/hellojpackage
```
