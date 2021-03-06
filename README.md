# Getting Started with biicode 

biicode's getting started code. You can read the full guide in [biicode docs](http://docs.biicode.com/c++/gettingstarted.html).

To try this out just:

```
git clone https://github.com/MariadeAnton/unit_test
cd unit_test
bii init -L
bii build
```

`biicode.conf` and `CMakeLists.txt` files are everything your repo needs to work [@biicode](www.biicode.com) - [Developing with biicode guide](http://docs.biicode.com/c++/make_biicode_lib.html) comes in handy too. 

**bii/find** branch tests how to get started with biicode, whole #include routes and `bii find`.

To try it out just:

```
git clone https://github.com/MariadeAnton/unit_test
cd unit_test
git checkout bii/find
bii buzz
```

`bii buzz` is a command to ease up things at first, it runs:

```
bii init -L
bii find
bii build
```

Note: This process creates `biicode.conf` and `CMakeLists.txt` files.

