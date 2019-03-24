# Soliloquy Artifacts

This repository contains Maven Artifacts for Soliloquy engine specifications, and implementations of those specifications (e.g. the Inaugural engine).

## Getting Started

When developing a Soliloquy game, or an engine component, create your project as a Maven project, and declare the following in the POM:

```
  <repositories>
    <repository>
        <id>github-mvn-repo</id>
        <url>https://raw.githubusercontent.com/felix-t-morgenstern/soliloquy.artifacts/master/</url>
        <releases>
            <enabled>true</enabled>
        </releases>
        <snapshots>
            <enabled>false</enabled>
        </snapshots>
    </repository>
  </repositories>
```

### Prerequisites

* [Maven](https://maven.apache.org/) - Dependency Management

### Installing

This project is simply a collection of artifacts; no special installation steps are required.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the tags on this repository.

## Contributing

A section on contributing to this project will be added at a later date (when a full release version is finalized).

## Authors

All authors are welcome. Authors will be identified by contributions to the repository. Authors are welcome to identify themselves in the documentation of classes to which they have substantially contributed. At present, no formal or typical procedure exists by which contributions are verified or permitted.

## License

A license for open and free use is under consideration; at present, it has not been finalized, and therefore this code remains private property. This will be hashed out prior to the release of the first full version.
