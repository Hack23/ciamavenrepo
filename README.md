# Hack23 CIAMavenRepo

This repository contains custom builds and patch builds of dependencies used in the [Hack23/cia](https://github.com/Hack23/cia) project.

## Purpose

The purpose of this repository is to provide patched and customized builds of libraries and frameworks that are not available in public Maven repositories. This ensures that the [Hack23/cia](https://github.com/Hack23/cia) project has access to the specific versions of dependencies required for its development.

## Custom Builds

Currently, the repository includes custom builds of the following forks with patches:

1. [ContiPerf](https://github.com/pethers/contiperf) - A performance testing library for Java projects.
2. [dchartsclone](https://github.com/pethers/dchartsclone) - A library for creating dynamic and interactive charts in Java applications.

## Usage

To use the custom builds in your Maven project, add the following repository configuration to your `pom.xml`:

```xml
<repositories>
    <repository>
        <id>hack23-ciamavenrepo</id>
        <url>https://github.com/Hack23/ciamavenrepo/raw/main/</url>
    </repository>
</repositories>
