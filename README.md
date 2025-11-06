# OofScoop - Custom Scoop Bucket

[![Tests](https://github.com/rafalohaki/oofscoop/actions/workflows/ci.yml/badge.svg)](https://github.com/rafalohaki/oofscoop/actions/workflows/ci.yml) [![Excavator](https://github.com/rafalohaki/oofscoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/rafalohaki/oofscoop/actions/workflows/excavator.yml)

Custom bucket for [Scoop](https://scoop.sh), containing specialized packages and versions.

## Available Packages

- **graalvm25** - GraalVM Community Edition 25.x (High-performance polyglot VM)

## How to use this bucket

First, add the bucket to your Scoop installation:

```pwsh
scoop bucket add oofscoop https://github.com/rafalohaki/oofscoop
```

Then install packages from this bucket:

```pwsh
scoop install oofscoop/graalvm25
```

## Package Details

### GraalVM 25

GraalVM Community Edition 25.x - A high-performance, embeddable, polyglot Virtual Machine that supports:
- JVM languages (Java, Scala, Kotlin)
- JavaScript/NodeJS
- Python, Ruby, R
- LLVM languages (C, C++, Rust)

**Installation:**
```pwsh
scoop install oofscoop/graalvm25
```

**Environment Variables Set:**
- `JAVA_HOME` - Points to GraalVM installation
- `GRAALVM_HOME` - Points to GraalVM installation
- `PATH` - Adds GraalVM bin directory

## Contributing

To contribute new manifests or improvements:

1. Fork this repository
2. Create new manifests in the `bucket/` directory
3. Test your manifests locally
4. Submit a pull request

For manifest creation guidelines, see:
- [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
- [App Manifests Wiki](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)

## License

This project is licensed under the Unlicense - see the [LICENSE](LICENSE) file for details.
