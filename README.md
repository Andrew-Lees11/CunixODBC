# CunixODBC

Swift module maps for [unixODBC](https://github.com/lurcher/unixODBC), which allow you to use the unixODBC C library in your Swift project.

Note - from Swift 4.2 you can pull the unixODBC library directly into your Swift project and will not need to use this repository (you can see an example of this in [Swift-Kuery-PostgreSQL](https://github.com/IBM-Swift/Swift-Kuery-PostgreSQL/tree/master/Sources/CLibpq)).

## Usage

#### Add dependencies

Add the `CunixODBC` package to the dependencies within your application’s `Package.swift` file. Substitute `"x.x.x"` with the latest `CunixODBC` [release](https://github.com/Andrew-Lees11/CunixODBC/releases).

```swift
.package(url: "https://github.com/Andrew-Lees11/CunixODBC.git", from: "x.x.x")
```

Add `CunixODBC` to your target's dependencies:

```swift
.target(name: "example", dependencies: ["CunixODBC"]),
```

#### Import package

```swift
import CunixODBC
```

## Community

We love to talk server-side Swift, and Kitura. Join our [Slack](http://swift-at-ibm-slack.mybluemix.net/) to meet the team!
