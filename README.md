# Building a Blockchain from Scratch in Go 

A hands-on, handwritten implementation of blockchain primitives in Golang based on tutorials by Akhil Sharma.

## Project Structure
- `/01-basic-blockchain`: Simple blockchain ledger using SHA-256 hashing and HTTP endpoints (`gorilla/mux`).
- `/02-proof-of-work`: Advanced build introducing Proof-of-Work (PoW) consensus, difficulty targeting, nonces, and thread-safe mining using `sync.Mutex`.

## Features Covered
- Cryptographic hash chaining (`crypto/sha256`)
- Concurrency & Thread Safety (`sync.Mutex`)
- RESTful APIs (`gorilla/mux`)
- Mining algorithm & Difficulty validation