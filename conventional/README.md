<p align="center">
  <img src= "https://github.com/thrustlang/.github/blob/main/assets/logos/thrustlang-logo-name.png" alt= "logo" style= "width: 2hv; height: 2hv;"> </img>
</p>

# Thrust Programming Language | Roadmap > Conventional Programming

This article will explain the biggest and most game-changing developments in mainstream programming that Thrust has to offer the world.

> [!WARNING]  
> These enormous development stages in the development of the language and compiler do not influence its early deployment to BETA.

## When will Thrust come out?

Thrush will be released when the compiler and language are deemed to have the minimum C capability to interoperate with core code. In addition, all the capabilities needed to interoperate with external code have been mapped, making Thrust an extensible and usable language with real code from other programming languages.

It should be noted that this does not include certain new features in C, such as macros and compile-time execution.

As of this writing, the compiler and language are not that far from this stage. Please be patient.

If you want to accelerate development, it is recommended to support the developer with technical or financial expertise.

For example, offering to develop language and syntax documentation, without getting involved in the compiler.

In any case, Thrust is soon to be released.

------------------

### Cbindgen

A new feature in Thrush, this will allow the compiler to export C production code to native Thrush code, allowing for full C integration into Thrust.

For more information, see: `cbindgen/README.md`

### Compile Time Code Executation

A new feature of Thrush, which will allow code execution at compile time, enabling support for dynamic code execution. This bridges the current breachs in many programming languages ​​related to compile-time evaluation.

For more information, see: `compiletime/README.md`

### C Code Execution

A new feature from Thrust, which will allow you to compile C directly from the Thrust compiler. It is heavily inspired by the implementation of the [D Programming Language](https://dlang.org).

For more information, see: `cexecution/README.md`

### Bootstrapping

It refers to the compiler technique of writing a primary compiler, then writing the main compiler in the same language. For these reasons, Rust is built in Rust.

For more information, see: `cexecution/README.md`

Reference: https://bootstrappable.org

------------------

## Highlight

### Cbindgen

This will allow Thrust to interoperate with production C code using just one import. This system preprocesses C type headers to integrate them into the Thrust compiler's front-end AST.

An example of its use can be seen as follows:

```rust
importC "raylib.h";
```
