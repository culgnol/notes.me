# notes.me

Me adding notes.

My notes so far...
* [Notetaking](notetaking/notetaking.md)

Awesome Lists
* https://github.com/sindresorhus/awesome
* https://github.com/bayandin/awesome-awesomeness

Build (search) notes myself (use the following terminal commands to find tags and files):

1a. Find all docs with string "tag::", returns a list of the file names and paths
```
grep -iRl  "tag::" .
// i - ignore case
// R - recursive file search
// l - show file names instead of content
```

1b. Find all tags in docs
```
grep -o "tag::.*.\[\]" snippet_20190328.adoc
```

1c. Find all strings matching "tag::" in all docs and filters out duplicates
```
grep -iRoh  "tag::[A-Za-z]*\[\]" . | sort --unique
```

Tags accumulated so far:
```
tag::tagname[]
tag::code[]
tag::javascript[]
tag::csharp[]
tag::javascript[]
tag::csharp[]
tag::typescript[]
tag::fsharp[]
tag::python[]
tag::javascript[]
tag::csharp[]
tag::typescript[]
tag::fsharp[]
tag::python[]
tag::javascript[]
tag::csharp[]
tag::javascript[]
tag::csharp[]
tag::typescript[]
tag::fsharp[]
tag::neuralnetwork[]
```

#### Props
[@jordanorelli]: [Zombie Approach](https://gist.github.com/jordanorelli/11229304)
