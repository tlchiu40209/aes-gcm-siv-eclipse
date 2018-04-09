# aes-gcm-siv-eclipse
A slight fix of Codahale's AES-GCM-SIV project to be Java 10 Compatible and can import into Eclipse directly.

Disclaimer:
I do not conduct this code. All progress is done by Mr. Codahale.
See [Codahale's AES-GCM-SIV](https://github.com/codahale/aes-gcm-siv) for more.

What have I done to it:
  - Basic Project Settings for Eclipse
  - Related JAR API included.

Software Environment:
  - OS Independent
  - Eclipse >= 4.7
  - Java 9 - 10 (Java 11 incompatible)*

Eclipse Configuration:
  - JDK Compliance Level: 9
  - Installed JREs: jre-10 (Need to configure it manually)
  
*Java 10 complains about the illegal reflective access by org.openjdk.jmh.util.Utils and noted that all illegal access operations will be denied in future release of Java.
