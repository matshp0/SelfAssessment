## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js: 👂 heard
  - Stateful and stateless servers: 👂 heard
  - Nonblocking I/O and blocking code: 🎓 known
  - Event loop phases: 🎓 known
  - Event loop microtasks and macrotasks: 🎓 known
  - Garbage collection: 🖐️ used
  - Node.js LTS schedule
  - I/O-bound, CPU-bound, memory-bound tasks
  - Interactive applications (close to real-time)
- Modularity, layers and dependencies
  - CommonJS modules: 🎓 known
  - ECMAScript modules: 🎓 known
  - Module `node:module`
  - Caching in CJS and ESM
  - Modules as singletons
  - Contexts and scripts module `node:vm`: 👂 heard
  - Dependencies: `npm`, `node_modules`: 🎓 known
  - Files `package.json`, `package-lock.json`: 🎓 known
  - Module-based permissions model
  - Isolation with modularity
  - Dependency injection: 👂 heard
  - DI containers
  - Coupling and cohesion
  - Framework agnostic approach
- Environment
  - Command line arguments
  - Node.js CLI: 👂 heard
  - Process-based permissions
  - Graceful shutdown: 🎓 known
  - Clustering: 👂 heard
  - Watch filesystem changes with --watch: 👂 heard
- Internal API
  - Streams API: 👂 heard
  - Web Streams API
  - Crypto API: 👂 heard
  - Password hashing with crypto.scrypt
  - Web Crypto API
  - File system API (sync and async): 🎓 known
  - Copy folder recursively
  - Worker threads: 👂 heard
  - Performance hooks
  - Native fetch and nodejs/undici: 👂 heard
  - async_hooks
  - AsyncLocalStorage
  - AsyncResource
  - Deprecated domain API
  - Node.js single executable
  - SharedArrayBuffer
  - Module `node:worker_threads`
  - Module `node:child_process`
  - MessageChannel, MessagePort
  - BroadcastChannel
  - Generating crypto random UUID
  - Module `node:url` vs `new URL`
  - Module `node:assert`
  - Internationalization
  - Blob, File, Buffer, module `node:buffer`
  - Module `node:zlib`
- Network
  - Endpoint throttling
  - ALPN
  - SNI callback
  - SSL certificates
  - Protocol agnostic approach
  - Fetch API
  - IncomingMessage
  - HTTP(S): 🎓 known
  - TCP/SSL: 👂 heard
  - UDP: 🎓 known
  - TLS: 👂 heard
  - Websocket: 🎓 known
  - SSE
  - HTTP/3 (QUIC)
  - Long polling: 🖐️ used
  - REST: 🎓 known
  - RPC
  - Routing: 🎓 known
  - DoS
  - DDoS
  - XSS
  - Path traversal
  - CSRF
  - DNS: 🖐️ used
  - SQL injection
  - noDelay
  - keep-alive: 👂 heard
  - IP sticky sessions: 👂 heard
- Technique and tools
  - Native test runner
  - Logging: 👂 heard
  - Application configuring
  - Testing
  - CI/CD
  - Readable: 🖐️ used
  - Writable: 🖐️ used
  - Transform: 🎓 known
  - Back pressure
  - Buffer: 🖐️ used
  - Console: 🖐️ used
  - Inspector
- Data access
  - Data access layer
  - Repository
  - Active record
  - Query builder
  - Object-Relational Mapping
  - CRUD
  - DTO
- Error handling and debugging
  - `Error`: 🖐️ used
  - `error.cause`: 🎓 known
  - `error.code`
  - `error.message`
  - `error.stack`
  - `Error.captureStackTrace`
  - How to avoid mixins
  - Uncaught exceptions
  - Heap dump
  - Debugging tools
  - Flame graph
  - Memory leaks: 🎓 known
  - Resource leaks
  - Data race
- Integrations and bindings
  - Native addons: 👂 heard
  - `C` and `C++` addons
  - `Rust` addons
  - `Zig` addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI `C` and `C++`
  - NAPI `Rust`
  - NAPI `Zig`
  - Webassembly `WAT`
  - Webassembly `C` and `C++`
  - Webassembly `Rust`
  - Webassembly `Zig`
  - Webassembly `AssemblyScript`
  - Shared memory
  - V8 binary serialization
