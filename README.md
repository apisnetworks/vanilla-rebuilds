These are binaries built from [Vanilla Forums](https://github.com/vanilla/vanilla). To build, run bin/release.sh from their source tree.

Note, when building Quill checksum is off. Related possibly to [yarnpkg/berry#2774](https://github.com/yarnpkg/berry/issues/2774#issuecomment-822472844). Issue is not present on older Vanilla rebuilds that use classic Yarn. This check may be bypassed by adding YARN_CHECKSUM_BEHAVIOR=ignore.

Built against Node v18.
