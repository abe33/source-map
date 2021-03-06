# Change Log

## 0.1.27

* Don't throw an error when the `file` property is missing in SourceMapConsumer,
  we don't use it anyway.

## 0.1.26

* Fix SourceNode.fromStringWithSourceMap for empty maps. Fixes github issue 70.

## 0.1.25

* Make compatible with browserify

## 0.1.24

* Fix issue with absolute paths and `file://` URIs. See
  https://bugzilla.mozilla.org/show_bug.cgi?id=885597

## 0.1.23

* Fix issue with absolute paths and sourcesContent, github issue 64.

## 0.1.22

* Ignore duplicate mappings in SourceMapGenerator. Fixes github issue 21.

## 0.1.21

* Fixed handling of sources that start with a slash so that they are relative to
  the source root's host.

## 0.1.20

* Fixed github issue #43: absolute URLs aren't joined with the source root
  anymore.

## 0.1.19

* Using Travis CI to run tests.

## 0.1.18

* Fixed a bug in the handling of sourceRoot.

## 0.1.17

* Added SourceNode.fromStringWithSourceMap.

## 0.1.16

* Added missing documentation.

* Fixed the generating of empty mappings in SourceNode.

## 0.1.15

* Added SourceMapGenerator.applySourceMap.

## 0.1.14

* The sourceRoot is now handled consistently.

## 0.1.13

* Added SourceMapGenerator.fromSourceMap.

## 0.1.12

* SourceNode now generates empty mappings too.

## 0.1.11

* Added name support to SourceNode.

## 0.1.10

* Added sourcesContent support to the customer and generator.

