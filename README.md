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

References
----------

- [Official website of Ocaml](https://ocaml.org)
- [Learn Ocaml](https://ocaml.org/learn/)
