# Languages

Quick reference for programming languages

Currently Github doesn't support the `include` directive of AsciiDoc:

* https://github.com/github/markup/issues/1095

For now, go to the [fragments](fragments/) directory to view the code snippets.

Alternatively, build or view the documents locally.

* [Show All Fragments](templates/all.adoc)
* [C# Fragments](templates/csharp.adoc)
* [Javascript Fragments](templates/javascript.adoc)

Creation pattern for the fragment files:
```
// tag::javascript[]
ifdef::javascript,showall[]

=== TBD

endif::[]
// end::javascript[]

// tag::csharp[]
ifdef::csharp,showall[]

=== TBD

endif::[]
// end::csharp[]

// tag::typescript[]
ifdef::typescript,showall[]

=== TBD

endif::[]
// end::typescript[]

// tag::fsharp[]
ifdef::fsharp,showall[]

=== TBD

endif::[]
// end::fsharp[]
```


---

[\[:house:\]](../README.md)
