# org.jabref.gui.customjfx.support

This project generates the library "customfx.jar", which is intended to be used in the context of JabRef to address a [java bug](https://bugs.openjdk.java.net/browse/JDK-8185792):
Linux users could not enter accented characters in the entry editor and the search bar [jabref#3028](https://github.com/JabRef/jabref/issues/3028).
The usage in JabRef can be seen at [jabref#3128](https://github.com/JabRef/jabref/pull/3128).

[org.jabref.gui.customjfx.support.InputMethodSupport](src/main/java/org/jabref/gui/customjfx/support/InputMethodSupport.java) is a direct copy from the openfjx code (http://hg.openjdk.java.net/openjfx/8/master/rt/file/tip/modules/swing/src/main/java/javafx/embed/swing/InputMethodSupport.java) without modifications.

The work is licensed as "GPL-2.0 WITH Classpath-exception-2.0".
Thus, if packaged as separate library and used as library, code making use of it may use a different license than GPL-2.0.
This is done here.

**Further reading**

- [linking exception](https://en.wikipedia.org/wiki/GPL_linking_exception) on WikiPedia
- OpenJFX license: http://hg.openjdk.java.net/openjfx/8/master/file/b80799b32c69/LICENSE#l326
