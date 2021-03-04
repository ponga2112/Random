#
## Hello World in 21 Languages ##
#

Python:
```
def hello():
  print("Hello World")

hello()
```
$ python3 ./hello.py
Hello World
```

Javascript:
```
console.log("Hello World");
```
$ node ./hello.js
Hello World
```

Java:
```
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```
$ javac HelloWorld.java
$ java HelloWorld
Hello World
```

C:
```
#include <stdio.h>
int main(void)
{ printf("hello World\n"); }
```
$ gcc hello.c -o hello.bin
$ ./hello.bin
Hello World
```

C#:
```
using System;
class Program {
  static void Main(string[] args) {
    Console.WriteLine("Hello World");
  }
}
```
> hello.exe
Hello World
```

C++:
```
#include <iostream>
int main()
{ std::cout << "Hello World\n";
    return 0; }
```
$ g++ hello.cpp -o hello.cbin
$ ./hello.cbin
Hello World
```

Go:
```
package main
import "fmt"
func main() {
    fmt.Println("Hello World")
}
```
$ go run hello.go
Hello World
```

R (Rscript):
```
cat("Hello World\n")
```
$ Rscript hello.r
Hello World
```

Swift:
```
import Foundation
print("Hello World")
```
$ swiftc hello.swift -o hello.capp
$ ./hello.capp
Hello World
```

PHP:
```
<?php
echo("Hello World\n");
?>
```
$ php hello.php
Hello World
```

Clojure:
```
(ns hello-world
   (:gen-class))
(defn hello-world []
   (println "Hello World"))
(hello-world)
```
$ clojure hello.clj
Hello World
```

Perl:
```
print "Hello World\n";
```
$ perl ./hello.pl
Hello World
```

Ruby:
```
puts("Hello World");
```
$ ruby ./hello.rb
Hello World
```

Rust:
```
fn main() {
    println!("Hello World");
}
```
$ rustc hello.rst -o hello.rbin
$ ./hello.rbin
Hello World
```

Assembly (NASM x86-64):
```
section     .text
global      _start
_start:
    mov     edx,len
    mov     ecx,msg
    mov     ebx,1
    mov     eax,4
    int     0x80
    mov     eax,1
    int     0x80
section     .data
msg     db  'Hello World',0xa
len     equ $ - msg
```
$ nasm -f elf64 -o hello.elf.o hello.asm
$ ld -s -o hello.elf hello.elf.o
$ ./hello.elf
Hello World

```

Haskell:
```
module Main where
main :: IO ()
main = putStrLn "Hello World"
```
$ ghc hello.hs -o hello.hbin
$ ./hello.hbin
Hello World
```

lua:
```
function hello ()
  return "Hello World"
end

print(hello())
```
$ lua hello.lua
Hello World
```

Scala:
```
object HelloS {
    def main(args: Array[String]) = {
        println("Hello World")
    }
}
```
$ scala HelloS
Hello World
```

Visual Basic:
```
Imports System
Module Hello
    Sub Main()
      Console.WriteLine("Hello World")
    End Sub
End Module
```
> hello.exe
Hello World
```

bash:
```
function Hello {
	echo "Hello World";
}

Hello
```
$ bash ./hello.sh
Hello World
```

powershell:
```
Write-Host "Hello World"
```
> ./hello.ps1
Hello World
```
