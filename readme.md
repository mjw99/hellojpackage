Example JPackage Maven project
==============================

Automatically built via the [GitHub Actions CI/CD](https://github.com/mjw99/hellojpackage/actions)

### Example building locally for Debian style system:
```
sudo apt-get install openjdk-17 maven bintuils fakeroot git
git clone https://github.com/mjw99/hellojpackage.git
cd hellojpackage
mvn clean package
sudo dpkg -i ./target/dist/*.deb
/opt/hellojpackage/bin/hellojpackage
```

## How to build the project via Maven on a Windows System
1) Install JDK >= 17 
2) Install Maven and ensure it is in your PATH
3) Download wix311-binaries.zip from WiX Toolset v3 releases  
(https://github.com/wixtoolset/wix3/releases) 
4) Unpack the archive into wix3 folder 
5) Add the wix3 folder to PATH environment variable

6) Clone and build the repo
```
git clone https://github.com/mjw99/hellojpackage.git
cd hellojpackage
mvn clean package
```
7) Run the installer that is created in the target/dist directory
