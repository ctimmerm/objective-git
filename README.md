# Objective Git - libgit2 wrapper for Objective-C
Objective Git provides Objective-C bindings to the libgit2 linkable C Git library.
It has been implemented as a framework right now. This is a good reference for
[setting up frameworks in xcode](http://atastypixel.com/blog/creating-applications-in-xcode-using-frameworks/).
This library follows the [rugged](https://github.com/libgit2/rugged) API as close
as possible while trying to maintain a native objective-c feel.

## Unit Testing
Unit testing in being done using [GHUnit](https://github.com/gabriel/gh-unit).
We are using both the mac and iOS unit testing frameworks. The one minor
inconvience to be aware of is that xcode doesn't like switching between
the mac test target and the iOS test target. You generally have to close
and reopen the project to move from iOS testing back to mac testing.

## libgit2
We are bundling the [libgit2][libgit2] binaries (static libraries) with
objective-git right now. This includes binaries compiled for os x and both the
iOS simulator and device.

[libgit2]: https://github.com/libgit2/libgit2

## Todo

## Contributing
Fork libgit2/objective-git on GitHub, make it awesomer (preferably in a branch named
for the topic), send a pull request.

## Authors
* Tim Clem <timothy.clem@gmail.com>

## License
MIT. See LICENSE file.
