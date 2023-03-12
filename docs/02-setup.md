# Instalasi dan Setup

## Download
### JDK
- https://www.oracle.com/id/java/technologies/downloads/

### IDE

**Netbean**
_Netbean_ adalah IDE yang cukup populer digunakan untuk pemrograman _Java_.
- https://netbeans.apache.org/download/index.html

**Eclipse**
_Eclipse_ adalah IDE alternatif digunakan untuk pemrograman _Java_.
- https://www.eclipse.org/downloads/packages/release/kepler/sr1/eclipse-ide-java-developers

**Notepad++**
_Notepad++_ adalah editor sederhana yang biasa digunakan untuk program-program Java yang relatif sederhana.
- https://notepad-plus-plus.org/downloads/


## Online
- https://www.programiz.com/java-programming/online-compiler/
- https://www.online-java.com/
- https://www.tutorialspoint.com/online_java_compiler.php

## Menjalankan Program Java Pertama Anda

Kita akan coba membuat dan menjalankan program _Java_ pertama kita. Untuk itu, buat program berikut, simpan dengan nama file `HelloWorld.java`. Untuk program sederhana, disarankan menggunakan editor _Notepad++_.

```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```

Program _Java_ ini akan dijalankan lewat _command prompt_. Dengan demikian buka _command prompt_ dan pastikan komputer Anda sudah bisa menjalankan program java, gunakan perintah `javac --version`. Versi _Java_ akan muncul sebagai output jika _Java Runtime_ sudah terpasang dengan benar pada komputer Anda.

![](images/02-javac-version.png)

Berikutnya, set folder aktif, ke lokasi folder dimana file `HelloWorld.java` disimpan (contoh: `C:\latihan`).
Sebelum program ini bisa dijakankan, ia perlu di-_compile_ terlebih dahulu. Untuk melakukan _compile_ gunakan perintah `javac HelloWorld.java`. Perintah ini akan menghasilkan file _byte code_ `HelloWorld.class`, dan untuk menjalankan file program hasil _compile_, gunakan perintah `java HelloWorld`.

```
C:\latihan>javac HelloWorld.java

C:\latihan>java HelloWorld
Hello, World!

```
