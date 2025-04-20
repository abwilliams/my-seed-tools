## README.md
Create a double mnemonic BIP39 seed. The 24 seed words can be split into two functioning 12 word seeds.

Code from https://stepansnigirev.github.io/seed-tools/double_mnemonic.html has been referenced.
# my-seed-tools


# Building

Compile it with:

```
wasm-pack build --target web
```

Then run http server:

```
python3 -m http.server
```

The website will be available on http://localhost:8000

Try it online at https://stepansnigirev.github.io/seed-tools/
