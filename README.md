unQLite
=======

[UnQLite](http://unqlite.org/) is a in-process software library which implements a self-contained, serverless, zero-configuration, transactional NoSQL database engine. UnQLite is a document store database similar to MongoDB, Redis, CouchDB etc. as well a standard Key/Value store similar to BerkeleyDB, LevelDB, etc.

UnQLite is an embedded NoSQL (Key/Value store and Document-store) database engine. Unlike most other NoSQL databases, UnQLite does not have a separate server process. UnQLite reads and writes directly to ordinary disk files. A complete database with multiple collections, is contained in a single disk file. The database file format is cross-platform, you can freely copy a database between 32-bit and 64-bit systems or between big-endian and little-endian architectures. UnQLite features includes:

* Serverless, NoSQL database engine.
* Transactional (ACID) database.
* Zero configuration.
* Single database file, does not use temporary files.
* Cross-platform file format.
* UnQLite is a Self-Contained C library without dependency.
* Standard Key/Value store.
* Document store (JSON) database via Jx9.
* Support cursors for linear records traversal.
* Pluggable run-time interchangeable storage engine.
* Support for on-disk as well in-memory databases.
* Built with a powerful disk storage engine which support O(1) lookup.
* Thread safe and full reentrant.
* Simple, Clean and easy to use API.
* Support Terabyte sized databases.
* BSD licensed product.
* Amalgamation: All C source code for UnQLite and Jx9 are combined into a single source file.

For details, see [http://unqlite.org](http://unqlite.org/)


