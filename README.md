# snake-rust-game (Comment utiliser)

### Dependencies

1. Installation rustup -> https://doc.rust-lang.org/book/ch01-01-installation.html

2. Installation "wasm-pack" -> `cargo install wasm-pack`

3. Installation npm dependencies -> `npm install` (Node JS doit etre installé) -> https://nodejs.org/)

### Compilation
Compiler le code Rust à chaque fois que des modifications sont apportées à `src/lib.rs`

4. Compiler le code rust en web-assembly -> `wasm-pack build --target web`

5. Lancer le serveur de developpement
`npm start`

6. Ouvrir le navigateur a l'addresse `localhost:8080`
