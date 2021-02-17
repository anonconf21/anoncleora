- Tests (snapshots) for in-memory and memory-mapped files calculations of embeddings ([#12]).
- Support for `NumPy` output format (available via `--output-format` program argument) ([#15]).
- Jupyter notebooks with experiments ([#16]).

### Improved
- Used `vector` for `hash_to_id` mappings, non-allocating cartesian product, `ryu` crate for faster write ([#13]).
- Sparse Matrix refactor (cleanup, simplification, using iter, speedup). Use Cargo.toml data for clap crate ([#17]).
- Unify and simplify embeddings calculation for in-memory and mmap matrices ([#18]).
- Fix clippy warnings ([#7]).

### Added
- JSON support ([#3]).
- Snapshot testing ([#5]).


- Initial release.
