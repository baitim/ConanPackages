<h1 align="center">Conan Packages</h1>

## Description

 Implementation of the storage of conan packages.

## How to use
1. conan package uploaded to my server
2. you can install it<br>
    <code>conan remote add conan_packages http://188.225.84.75:9300</code><br>
    <code>conan remote login conan_packages -n visitor -p visitor</code><br>
    <code>conan install --requires=\<project\>/\<version\> -r=conan_packages</code>

<p align="center"><img src="https://github.com/baitim/ConanPackages/blob/main/images/monkey.gif" width="40%"></p>

## Support
**This project is created by [baitim](https://t.me/bai_tim)**