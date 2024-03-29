# Hello World.rs
- `println! = This is a macro and we use "!" to declare a macros insted of funcionts`
- `rustc = This is the compiler of rust but it's used only in simple projects we used Cargo instead for manage rust projects`

# Cargo
- Cargo is a build and package manager system for manage Rust projects Cargo handles a lot of tasks for you, such as building your code, downloading the libraries your code depends on, and building those libraries.
- **Basic Commands of Cargo**:
    - `cargo new project_name` = This command is used to make a new project rust with the main.rs and cargo.toml file
    - The `Cago.toml` is used to store the configuration of Cargo this file have different sections the standard structure is: `[package]... [dependencies]...`
        - `[package]` = is a section heading that indicates that the following statements are configuring a package set the configuration information Cargo needs to compile your program: the name, the version, and the edition of Rust to use
        - `[dependencies]` = list any of your project’s dependencies
    - `cargo build` = command to make the build of the project (create the binary file)
    - `cargo run` = command to build and run the binary created
    - `cargo check` = command to build a project without producing a binary to check for errors.