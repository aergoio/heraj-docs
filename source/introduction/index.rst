Introduction
============

Install
-------

Maven
^^^^^

.. code-block:: xml

  <repositories>
    <repository>
      <id>jcenter</id>
      <url>https://jcenter.bintray.com</url>
    </repository>
  </repositories>

  ...

  <dependencies>
    <dependency>
      <groupId>io.aergo</groupId>
      <artifactId>heraj-transport</artifactId>
      <version>${herajVersion}</version>
    </dependency>
    <dependency>
      <groupId>io.aergo</groupId>
      <artifactId>heraj-wallet</artifactId>
      <version>${herajVersion}</version>
    </dependency>
    <dependency>
      <groupId>io.aergo</groupId>
      <artifactId>heraj-smart-contract</artifactId>
      <version>${herajVersion}</version>
    </dependency>
  </dependencies>

Gradle
^^^^^^

.. code-block:: groovy

  repositories {
    jcenter()
  }

  ...

  dependencies {
    implementation "io.aergo:heraj-transport:${herajVersion}"
    implementation "io.aergo:heraj-wallet:${herajVersion}"
    implementation "io.aergo:heraj-smart-contract:${herajVersion}"
  }