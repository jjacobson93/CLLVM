CLLVM
========

This Swift module wraps the C API for llvm

To use in your Swift package:
```swift
import PackageDescription

let package = Package(
    name: "YourPackage",
    dependencies: [
        // other dependencies here...
        .Package(url: "https://github.com/jjacobson93/CLLVM", majorVersion: 1)
    ]
)
```

License
---
MIT