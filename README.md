# hello-universe
A small repo dedicated to hello world projects of every language

# Running the universe

Since there's a lot here, the headers will be hyperlinked with the install guides, and the how to run below each header.

### [C](https://learn.microsoft.com/en-us/cpp/build/walkthrough-compile-a-c-program-on-the-command-line?view=msvc-170) | Compiled
---

```
cl ./c/helloworld.c
./c/helloworld
```

### [C++](https://learn.microsoft.com/en-us/cpp/build/walkthrough-compile-a-c-program-on-the-command-line?view=msvc-170) | Compiled
---

```
cl ./c++/helloworld.cpp
./c++/helloworld
```

### [C#](https://www.geeksforgeeks.org/how-to-execute-c-sharp-program-on-cmd-command-line/) | Compiled
---

```
csc ./c#/helloworld.cs
./c#/helloworld
```

### CSS, HTML, and Javascript
---
For all of these, navigate to the coresponding folder and open the index.html with your standard web browser.

### [Go](https://go.dev/doc/install)
---

```
go run ./go/helloworld.go
```

### [Java](https://docs.oracle.com/en/java/javase/21/install/installation-jdk-microsoft-windows-platforms.html#GUID-A740535E-9F97-448C-A141-B95BF1688E6F) | Compiled
---

```
javac ./java/HelloWorld.java
java ./java/HelloWorld
```

### [Perl](https://www.perl.org/get.html)
---
Perl is installed on most computers, to confirm it's on yours, check:

```
perl -v
```

To confirm it is installed on your computer

```
perl ./perl/helloworld.pl
```

### PHP
---
I don't know how to run php on your local without installing something huge, make a pull request to fix this if there is a simple way

### [Python](https://wiki.python.org/moin/BeginnersGuide/Download)
---

```
python ./python/helloworld.py
```

### [R](https://www.dataquest.io/blog/installing-r-on-your-computer/)
---

```
Rscript ./r/helloworld.R
```

### [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
---
This was a pain for me, I ended up using a windows ruby installer, but here's the doccumenation

```
ruby ./ruby/helloworld.rb
```

### [Rust](https://doc.rust-lang.org/book/ch01-01-installation.html) | Compiled
---

For rust:
```
rustc ./rust/helloworld.rs
./rust/helloworld
```

For the rust cargo project:
```
cd ./rust/hello_cargo
cargo build
./target/debug/hello_cargo
```

### [Zig](https://ziglang.org/learn/getting-started/).
---

```
zig run ./zig/helloworld.zig
```