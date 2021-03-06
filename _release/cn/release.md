---
title: "ServiceComb Releases"
lang: cn
ref: release
permalink: /cn/release/
excerpt: "ServiceComb Releases"
last_modified_at: 2019-04-06T00:50:43-55:00
---

使用以下链接从我们的一个镜像下载ServiceComb工具包版本。 您必须使用从我们的主分发目录下载的签名来验证下载文件的完整性。

主分发站点及其镜像仅提供当前推荐的版本。


**稳定发布版 - 最新版本:**

* [ServiceComb Service-Center 1.3.0](/cn/release/service-center-downloads/) (released on 2019-11-07)

* [ServiceComb toolkit 0.1.0](/cn/release/toolkit-downloads/) (released on 2019-09-04)

* [ServiceComb Pack 0.5.0](/cn/release/pack-downloads/) (released on 2019-08-26)

* [ServiceComb Java-Chassis 1.3.0](/cn/release/java-chassis-downloads/) (released on 2019-10-31)

* [ServiceComb Saga Actuator 0.3.0](/cn/release/saga-actuator-downloads/) (released on 2018-12-18)

* [ServiceComb Saga 0.2.1](/cn/release/saga-downloads/) (released on 2018-11-23)

* [ServiceComb Mesher 1.6.3](/cn/release/mesher-downloads/) (released on 2019-9-9)

* [ServiceComb Kie 0.1.0](/cn/release/kie-downloads/) (released on 2019-10-26)

**先前发行版本 :**

* [ServiceComb Service-Center 1.2.0](/cn/release/service-center-downloads/) (released on 2019-04-06)
* [ServiceComb Service-Center 1.1.0](/cn/release/service-center-downloads/) (released on 2018-11-30)
* [ServiceComb Service-Center 1.0.0](/cn/release/service-center-downloads/) (released on 2018-08-02)
* [ServiceComb Service-Center 1.0.0-m2](/cn/release/service-center-downloads/) (released on 2018-06-21)
* [ServiceComb Service-Center 1.0.0-m1](/cn/release/service-center-downloads/) (released on 2018-03-27)

* [ServiceComb Java-Chassis 1.2.1](/cn/release/java-chassis-downloads/) (released on 2019-05-19)
* [ServiceComb Java-Chassis 1.2.0](/cn/release/java-chassis-downloads/) (released on 2019-04-12)
* [ServiceComb Java-Chassis 1.1.0](/cn/release/java-chassis-downloads/) (released on 2018-11-30)
* [ServiceComb Java-Chassis 1.0.0](/cn/release/java-chassis-downloads/) (released on 2018-08-02)
* [ServiceComb Java-Chassis 1.0.0-m2](/cn/release/java-chassis-downloads/) (released on 2018-06-21)
* [ServiceComb Java-Chassis 1.0.0-m1](/cn/release/java-chassis-downloads/) (released on 2018-04-02)

* [ServiceComb Pack 0.4.0](/cn/release/pack-downloads/) (released on 2019-04-06)
* [ServiceComb Pack 0.3.0](/cn/release/pack-downloads/) (released on 2019-01-02)
* [ServiceComb Saga 0.2.0](/cn/release/saga-downloads/) (released on 2018-06-21)
* [ServiceComb Saga 0.1.0](/cn/release/saga-downloads/) (released on 2018-03-27)


**注意:**
  - 请查看 [兼容版本](/cn/release/compatibleversion) 获取版本兼容信息.


**验证发行版本**

使用PGP或SHA签名验证下载文件的完整性至关重要。可以使用GPG或PGP验证PGP签名。请下载[KEYS](https://www.apache.org/dist/servicecomb/KEYS) 以及相关发行版的asc签名文件。 建议从主发行版[目录](https://www.apache.org/dist/servicecomb/) 中获取这些文件，而不是从镜像中获取。
 ```
 gpg -import KEYS

 or

 pgpk -a KEYS

 or

 pgp -ka KEYS

```

要验证二进制文件/源，您可以从主分发目录下载相关的asc文件，并按照以下指南进行操作。

```
gpg --verify apache-servicecomb-********.asc apache-servicecomb-*********

or

pgpv apache-servicecomb-********.asc

or

pgp apache-servicecomb-********.asc


```

或者，您可以从主发行版[repo](https://www.apache.org/dist/servicecomb/)下载SHA签名，并使用sha512sum或者shasum验证下载。
