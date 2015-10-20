# learning-ocaml
Repository created in order to learn basics of Ocaml language

Installation on Ubuntu Linux
----------------------------

Required:

```
sudo apt-get install ocaml
```

Recommended:

```
sudo apt-get install ocaml-native-compilers ocaml-doc 
tuareg-mode ocaml-findlib oasis libpcre-ocaml-dev
```

Compiling and running programs
------------------------------

We can locate our program in file with `*.ml` extension. E.g. `my_prog.ml`.

When we want to compile this program, we should run the following command:

```
$ ocamlbuild my_prog.native
```

After that, we can run the program:

```
$ ./my_prog.native
```

Opam
----

[Opam](https://opam.ocaml.org/) is a package manager for Ocaml.

It can be installed with command:

```
sudo apt-get install opam
```

References
----------

- [Official website of Ocaml](https://ocaml.org)
- [Learn Ocaml](https://ocaml.org/learn/)
- [So you're learning Ocaml](http://hyegar.com/blog/2015/10/19/so-you%27re-learning-ocaml/)
