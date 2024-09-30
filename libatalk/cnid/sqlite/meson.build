libcnid_sqlite_sources = ['cnid_sqlite.c', 'sqlite3.c', 'sqlite3.h']

libcnid_sqlite = static_library(
    'cnid_sqlite',
    libcnid_sqlite_sources,
    include_directories: root_includes,
    dependencies: sqlite_deps,
    install: false,
)
