{:title "Table of Contents"
 :page-index 1
 :layout :page}

[The content](https://github.com/clojure-doc/clojure-doc.github.io) is a categorized and
manifold collection of documentation guides for the Clojure programming language and
its ecosystem.

We recognize that different Clojure users have different level of expertise
and separates content into several groups:

 * [Essentials](#essentials)
 * [Language Guides](#language-guides)
 * [Ecosystem & Tools](#the-clojure-ecosystem) (tools, libraries, community, books) guides
 * [Tutorials & Cookbooks](#tutorials-and-cookbooks)


## Essentials

Note that the editing environments are listed in alphabetical order and indicate no preference or endorsement. The last
["State of the Union" Clojure survey](https://clojure.org/news/2021/04/06/state-of-clojure-2021) indicated
that Emacs is still the most popular editing environment, followed by IntelliJ/Cursive, VS Code, Vim, and Atom.


### [Getting Started](/articles/tutorials/getting_started/)

If you're new to Clojure, this is a good place to start.


### [Introduction](/articles/tutorials/introduction/)

A swift introduction to the Clojure language, covering most of the
basics.

### [Atom for Clojure Development](https://atom.io/packages/chlorine)

The Chlorine package for Clojure development in Atom (via a Socket REPL).

### [IntelliJ / Cursive for Clojure Development](https://cursive-ide.com/userguide/)

The user guide for Cursive, the Clojure plugin for IntelliJ.

### [Emacs for Clojure Development](/articles/tutorials/emacs/)

A brief introduction to Emacs, Clojure mode, CIDER and Clojure development workflow with Emacs.

### [Vim for Clojure Development](/articles/tutorials/vim_fireplace/)

A brief introduction to Clojure development in Vim with fireplace.vim.

### [VS Code for Clojure Development](https://calva.io/)

The Calva extension for Clojure development in VS Code (via nREPL).



## Language Guides

### [Functions](/articles/language/functions/)

Functions are at the heart of Clojure.

This guide covers:

 * How to define functions
 * How to invoke functions
 * Multi-arity functions
 * Variadic functions
 * Higher order functions
 * Other topics related to functions


### [clojure.core Overview](/articles/language/core_overview/) (incomplete)

`clojure.core` is the core Clojure library.

This guide covers:

 * Key functions of `clojure.core`
 * Key macros of `clojure.core`
 * Key vars of `clojure.core`


### [Interoperability with Java](/articles/language/interop/)

The Clojure language implementation is symbiotic with its host
platform (the JVM), providing direct interoperability.

This guide covers:

 * How to instantiate Java classes
 * How to invoke Java methods
 * How to extend Java classes with proxy
 * How to implement Java interfaces with reify
 * How to generate Java classes with gen-class
 * Other topics related to interop


### [Namespaces](/articles/language/namespaces/)

Namespaces organize Clojure functions.

This guide covers:

 * An overview of Clojure namespaces
 * How to define a namespace
 * How to use functions in other namespaces
 * `require`, `refer` and `use`
 * How to Look up and invoke a function by name
 * Common compilation exceptions and their causes
 * How code compilation works in Clojure


### [Polymorphism: Protocols and Multimethods](/articles/language/polymorphism/)

This guide covers:

 * What are polymorphic functions
 * Type-based polymorphism with protocols
 * Ad-hoc polymorphism with multimethods
 * How to create your own data types that behave like core Clojure data types


### [Collections and Sequences](/articles/language/collections_and_sequences/)

This guide covers:

 * Collections in Clojure
 * Sequences in Clojure
 * Core collection types
 * Key operations on collections and sequences
 * Other topics related to collections and sequences


### [Concurrency & Parallelism](/articles/language/concurrency_and_parallelism/)

This guide covers:

 * An overview of concurrency hazards
 * Clojure's approach to state and identity
 * Immutable data structures
 * Reference types (atoms, vars, agents, refs)
 * Using Clojure functions with `java.util.concurrent` abstractions
 * The Reducers framework (Clojure 1.5+)
 * Other topics related to concurrency and runtime parallelism


### [Macros and Metaprogramming](/articles/language/macros/)

This guide covers:

 * Clojure macros
 * Clojure compilation process
 * Other topics related to metaprogramming


### [Laziness and Lazy Sequences](/articles/language/laziness/) (incomplete)

This guide covers:

 * What are lazy sequences
 * How to create functions that produce lazy sequences
 * How to force evaluation
 * Pitfalls with lazy sequences


### [Glossary](/articles/language/glossary/)

This guide includes definitons of various Clojure-related terminology.



## The Clojure Ecosystem

### [Books](/articles/ecosystem/books/)

This guide covers:

 * Books on Clojure
 * Books on ClojureScript


### [Getting Started with Leiningen](https://github.com/technomancy/leiningen/blob/master/doc/TUTORIAL.md)

This guide covers:

 * What is Leiningen and what it can do for you
 * How to create a project with Leiningen
 * How to manage project dependencies
 * Accessing the REPL
 * How to run tests for your project
 * How to run the app
 * How to compile your code and dependencies into a single JAR for deployment ("überjar")
 * How to share (publish) a library

### [Maven for Clojure Development](/articles/ecosystem/maven/)

This guide covers:

 * An overview of Apache Maven
 * Maven Clojure plugin

### [Clojure Library Directory](/articles/ecosystem/libraries_directory/)

A curated and highly opinionated categorized directory of available Clojure libraries and tools.

### [Clojure Community](/articles/ecosystem/community/)

This guide covers:

 * Planet Clojure, mailing lists, IRC channel
 * Clojure conferences
 * Local Clojure user groups
 * Other Clojure community resources

### [core.typed](/articles/ecosystem/core_typed/home/)

 * What is Clojure core.typed
 * core.typed documentation, tutorials, and guides.


### [java.jdbc](/articles/ecosystem/java_jdbc/home/)

This guide covers:

 * An overview of Clojure's JDBC wrapper
 * Setting up a data source
 * Manipulating data with SQL
 * Manipulating tables with DDL
 * How to use connection pooling
 * How to use some common DSLs with java.jdbc
 * Where to go beyond java.jdbc


### [Library Development and Distribution](/articles/ecosystem/libraries_authoring/)

This guide covers:

 * Basic setup for library development
 * How to publish a library to Clojars


### [Leiningen Profiles](https://github.com/technomancy/leiningen/blob/master/doc/PROFILES.md)

This guide covers:

 * What are Leiningen profiles
 * How to use them


### [Distributing Libraries with Leiningen](https://github.com/technomancy/leiningen/blob/master/doc/DEPLOY.md)

This guide covers:

 * How Clojure libraries are distributed
 * How to publish Clojure libraries to clojars.org
 * How to publish Clojure libraries to Maven Central
 * How to publish Clojure libraries to your own Maven repository


### [Writing Leiningen Plugins](https://github.com/technomancy/leiningen/blob/master/doc/PLUGINS.md)

This guide covers:

 * What Leiningen plugins can do
 * How to install Leiningen plugins
 * How to develop plugins
 * How to distribute plugins


### [Documentation Tools](/articles/ecosystem/generating_documentation/)

 * Tools for generating documentation from docstrings and other project
metadata.


### [Data Processing (Overview)](/articles/ecosystem/data_processing/) (TBD)

This guide covers:

 * An overview of why Clojure is an excellent choice for data processing
 * Popular tools and libraries in the area



### [Clojure User Groups](/articles/ecosystem/user_groups/)

This guide covers:

 * Clojure User Groups (CLJUGs) around the world



## Tutorials and Cookbooks

### [Basic Web Development](/articles/tutorials/basic_web_development/)

A brief tutorial/walkthrough of building a small web app using Ring,
Compojure, Hiccup, and H2.

### [Parsing XML in Clojure](/articles/tutorials/parsing_xml_with_zippers/)

This guide covers:

 * How to parse XML in Clojure with zippers (`clojure.data.zip`)

### [Growing a DSL with Clojure](/articles/tutorials/growing_a_dsl_with_clojure/)

How to create a simple DSL with Clojure.

Includes introductions to:

 * Multimethods
 * Hierarchies
 * Metaprogramming and the "Code as data" philosophy


### [Strings](/articles/cookbooks/strings/)

This cookbook covers:

 * How to work with strings
 * How to work with characters
 * How to work with regular expressions
 * How to work with context-free grammars
 * How to format text

### [Mathematics](/articles/cookbooks/math/)

Includes coverage of facilities for doing math with Clojure.


### [Data Structures](/articles/cookbooks/data_structures/) (TBD)

This cookbook covers:

 * Vectors
 * Maps
 * Lists
 * Sets
 * Generic operations on sequences

### [Files and Directories](/articles/cookbooks/files_and_directories/)

This cookbook covers:

 * Reading and writing text and binary files
 * Listing directory contents
 * Creating files and directories
 * Moving files and directories
 * Removing files and directories
 * Accessing file metadata
 * Other operations on files and directories


### [Date and Time](/articles/cookbooks/date_and_time/) (TBD)

This guide covers:

 * Working with JDK dates
 * Working with Joda Time and `clj-time`
 * Instant literals (Clojure 1.4+)



### [Middleware](/articles/cookbooks/middleware/) (incomplete)

This guide covers:

 * What middleware is and how it works
 * Creating middleware for a client function
 * Combining middleware to create a new client


## License

All the content is distributed under the
[CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) license
and are copyright their respective primary author(s).


## Tell Us What You Think!

Please take a moment to tell us what you think about this guide on the [Clojurians Slack `#clojure-doc` channel](https://clojurians.slack.com/archives/C02M6N5C137) or the [Clojure mailing list](https://groups.google.com/group/clojure).

Let us know what was unclear or what has not been covered. Maybe you do not like the guide style or grammar or discover spelling mistakes.
Reader feedback is key to making the documentation better.
