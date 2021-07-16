Code Conventions
===================

Every major open-source project has its own style guide: a set of conventions
(sometimes arbitrary) about how to write code for that project. It is much
easier to understand a large codebase when all the code in it is in a
consistent style.

“Style” covers a lot of ground, from “use camelCase for variable names” to
“never use global variables” to “never use exceptions.” This project links to the
([google/styleguide](https://github.com/google/styleguide)) guidelines.

This project holds the [Java Style Guide](java/javaguide.html) and [Frontend ESLint config](javascript/README.md).

If your project requires that you create a new XML document format, the [XML
Document Format Style Guide](xml/xmlstyle.html) may be helpful. In addition to actual style
rules, it also contains advice on designing your own vs. adapting an existing
format, on XML instance document formatting, and on elements vs. attributes.

The style guides in this project is derived from ([google/styleguide](https://github.com/google/styleguide)) and licensed under the CC-By 3.0 License,
which encourages you to share these documents.
See [https://creativecommons.org/licenses/by/3.0/][ccl] for more details.

### How to Use
**Eclipse**: Import [eclipse-java-google-style.xml](java/eclipse-java-google-style.xml) and [imports.importorder](java/imports.importorder) to your project settings
**IntelliJ**: Import [intellij-java-google-style.xml](java/intellij-java-google-style.xml) to your project settings
**Freonted**: [README.md](javascript/README.md)

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>

[ccl]: https://creativecommons.org/licenses/by/3.0/