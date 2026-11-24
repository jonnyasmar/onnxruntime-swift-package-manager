> [!NOTE]
> **About this copy.** This repository is a copy of Microsoft's
> [onnxruntime-swift-package-manager](https://github.com/microsoft/onnxruntime-swift-package-manager)
> (MIT License, © Microsoft Corporation) at version **1.24.2**. It is hosted here because the original
> repository and its binary downloads on `download.onnxruntime.ai` are no longer available.
> It is not affiliated with or endorsed by Microsoft.
>
> The source is unmodified, apart from this note and the two `binaryTarget` URLs in `Package.swift`.
> Those URLs now point at this repository's [1.24.2 release](https://github.com/jonnyasmar/onnxruntime-swift-package-manager/releases/tag/1.24.2),
> which holds byte-identical copies of Microsoft's original archives. The checksums are unchanged,
> and SwiftPM verifies them on every download:
>
> | Archive | SHA-256 |
> | --- | --- |
> | `pod-archive-onnxruntime-c-1.24.2.zip` | `f7100a992d2a8135168c8afd831e6a58b465349101982aa58b3e11d36e600b54` |
> | `pod-archive-onnxruntime-extensions-c-0.13.0.zip` | `346522d1171d4c99cb0908fa8e4e9330a4a6aad39cd83ce36eb654437b33e6b5` |
>
> Microsoft's history is kept as it was. Their 1.24.2 release commit (`b7fb7f7`) is tagged
> `microsoft-1.24.2`, and the `1.24.2` tag is the commit on top of it that repoints the URLs.
> Each archive includes Microsoft's `LICENSE`. Microsoft's README follows, unchanged.

# Swift Package Manager for ONNX Runtime

A light-weight repository for providing [Swift Package Manager (SPM)](https://www.swift.org/package-manager/) support for [ONNXRuntime](https://github.com/microsoft/onnxruntime). The ONNX Runtime native package is included as a binary dependency of the SPM package.


SPM is the alternative to CocoaPods when desired platform to consume is mobile iOS.

## Note

The `objectivec/` directory is copied from the [ORT repo](https://github.com/microsoft/onnxruntime/tree/main/objectivec) and it's expected to match. It will be updated periodically/before release to merge new changes.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
