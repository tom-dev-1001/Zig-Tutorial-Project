Zig Tutorial Project

This repository is a hands-on Zig tutorial project designed to demonstrate
core Zig concepts through executable examples.

The project is structured as a collection of self-contained modules, each
focused on a specific language feature. The main entry point allows you to
enable or disable individual sections to explore them one at a time.


PROJECT GOAL

This project is intended as a practical learning resource rather than a
theoretical overview.

It focuses on:
- Explicitness over magic
- Real code that runs
- Showing how Zig behaves in practice
- Exploring language features in isolation


PROJECT STRUCTURE

main.zig

The main entry point for the tutorial. Each tutorial module exposes a `run()`
function that can be enabled or disabled by commenting or uncommenting calls
in main().

Example usage:

- Uncomment a single module call
- Run the program
- Observe the output
- Move on to the next topic


TUTORIAL MODULES

Each topic lives in its own file and demonstrates a specific area of Zig.

Included modules:

**Variables.zig** - Variable declarations, mutability, types, arrays and slices, conversion  
**loops.zig** - for loops, while loops  
**branching.zig** - if expressions, switch statements
**functions.zig** - Function declarations, Parameters, Return values

structs.zig
- Struct definitions
- Field access
- Struct initialization

errors.zig
- Error unions
- Error handling with catch
- Explicit error propagation

allocation.zig
- Allocators
- Heap vs stack allocation
- Manual memory management

arrayLists.zig
- Dynamic arrays
- ArrayList usage
- Capacity vs length

pointers.zig
- Pointer basics
- Const vs mutable pointers
- Dereferencing

comptime.zig
- Compile-time execution
- comptime parameters
- Compile-time logic

OpeningFiles.zig
- File IO
- Reading files
- Error handling with IO

threading.zig
- Basic threading concepts
- Interaction with shared data

optionals.zig
- Optional types
- null handling
- Safe unwrapping

input.zig
- Reading user input
- Handling stdin

output.zig
- Printing
- Debug output

Floats.zig
- Floating point types
- Precision considerations


RUNNING THE PROJECT

To run the tutorial:

1. Open a terminal in the project directory
2. Run the following command:

zig run main.zig

To explore a topic:
- Open main.zig
- Uncomment the desired module’s run() call
- Comment out the others
- Run the program again


DESIGN NOTES

- Each module is intentionally verbose and explicit
- Code prioritizes clarity over brevity
- Many examples intentionally print types and values to show Zig behavior
- Error cases are demonstrated explicitly rather than hidden


INTENDED AUDIENCE

This project is aimed at:
- Programmers new to Zig
- Developers coming from C / C++ / Rust
- Anyone who prefers learning by running real code


STATUS

This is a complete and functional tutorial project created as a learning
exercise and reference implementation.
