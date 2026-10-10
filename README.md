# treebinder
A convenient parser generator for Rust that compiles a grammar, written in a dedicated macro DSL, into minimal LR(1) tables at compile time. Built on runeweaver, it consumes its token stream and produces typed ASTs from your own structs and enums.
