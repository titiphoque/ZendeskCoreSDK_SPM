# ZendeskCoreSDK_SPM

SPM Package to make ZendeskCoreSDK available via SPM

## Installation

```swift
dependencies: [
    .package(
        name: "ZendeskCoreSDK", url: "https://github.com/titiphoque/ZendeskCoreSDK_SPM", 
        .upToNextMajor(from: "2.4.1")
    )
]
```

and in `target` :

```swift
dependencies: [
    .product(name: "ZendeskCoreSDK", package: "ZendeskCoreSDK"),
]
```