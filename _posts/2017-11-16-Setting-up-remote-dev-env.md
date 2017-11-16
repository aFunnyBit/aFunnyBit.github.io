---
layout: post
title: Setting Up A Remote Development Environment
tags: ["linux","networking"]
---

![Hero_Image](https://tecadmin.net/wp-content/uploads/2014/01/ssh-large-image.gif "hero_image")

In the post we are going to explain you in details – How to Configure and use OpenSSH on CentOS 7. Secure Shell or SSH is a protocol which allows users to connect to a remote system.

The login session is encrypted and very secure. In this blog post I would like to demonstrate how to congifigure a CentOS7 machine with OpenSSH and a good baseline toolchain for developing on.

### Installation

Getting the appropriate packages:

```
# yum install openssh openssh-server openssh-clients openssl-libs
```


### Configuration

First things first, back up your sshd configuration file like so:

```
# cp /etc/ssh/sshd_config /etc/ssh/sshd_config.orig
```
