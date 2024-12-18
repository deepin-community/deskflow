# Build Deskflow

## Developer Quick Start

Deskflow is free and open source software, and anyone is welcome to build it,
run it, tinker with it, redistribute it as part of their own app, etc.

These instructions will build Deskflow, which doesn't require a license
or serial key. Check the [Build Guide](https://github.com/deskflow/deskflow/wiki/Build-Guide)
wiki page if you have problems.

**1. Dependencies:**

*Linux, macOS, or BSD-derived:*
```
./scripts/install_deps.sh
```

*Windows:*
```
python scripts/install_deps.py
```

**2. Configure:**

*Linux, macOS, or BSD-derived:*
```
cmake -B build
```

*Windows:*
```
cmake -B build --preset=windows-release
```

**3. Build:**
```
cmake --build build -j8
```

**4. Test:**
```
./build/bin/unittests
./build/bin/integtests
```

**5. Run**
```
./build/bin/deskflow
```
