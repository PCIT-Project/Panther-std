# Change Log

<!---------------------------------->
<a name="v0.0.17.0"></a>
## v0.0.17.0
- Added asserts module
	- `assert`
- Added compiler-rt for panic
- Added asserts to `ArrayRefIter` and `MutArrayRefIter`
- Added asserts to `mem.copyBuffer` and `mem.moveBuffer`


<!---------------------------------->
<a name="v0.0.16.0"></a>
## v0.0.16.0
- Added `mem` module
	- Added `mem.copyBuffer`
	- Added `mem.moveBuffer`
- Added to `types module`
	- Added `types.isDefaultInitializable()`
	- Added `types.isTriviallyDefaultInitializable()`
	- Added `types.isComptimeDefaultInitializable()`
	- Added `types.isNoErrorDefaultInitializable()`
	- Added `types.isSafeDefaultInitializable()`
	- Added `types.isTriviallyDeletable()`
	- Added `types.isComptimeDeletable()`
	- Added `types.isCopyable()`
	- Added `types.isTriviallyCopyable()`
	- Added `types.isComptimeCopyable()`
	- Added `types.isNoErrorCopyable()`
	- Added `types.isSafeCopyable()`
	- Added `types.isMovable()`
	- Added `types.isTriviallyMovable()`
	- Added `types.isComptimeMovable()`
	- Added `types.isNoErrorMovable()`
	- Added `types.isSafeMovable()`
	- Added `types.isComparable()`
	- Added `types.isTriviallyComparable()`
	- Added `types.isComptimeComparable()`
	- Added `types.isNoErrorComparable()`
	- Added `types.isSafeComparable()`


<!---------------------------------->
<a name="v0.0.15.0"></a>
## v0.0.15.0
- Updated compiler-rt iterators and container iterators to reflect updates to [PCIT-CPP v0.0.231.0](https://github.com/PCIT-Project/PCIT-CPP/blob/main/CHANGELOG.md#v0.0.231.0)


<!---------------------------------->
<a name="v0.0.14.0"></a>
## v0.0.14.0
- Updated type aliases and function aliases to reflect updates to [PCIT-CPP v0.0.229.0](https://github.com/PCIT-Project/PCIT-CPP/blob/main/CHANGELOG.md#v0.0.229.0)


<!---------------------------------->
<a name="v0.0.13.0"></a>
## v0.0.13.0
- Added alias for `bit.bitCast`


<!---------------------------------->
<a name="v0.0.12.0"></a>
## v0.0.12.0
- Added `ArrayRefIter` and `MutArrayRefIter`
- Updated compiler-rt iterators to reflect fixes in [PCIT-CPP v0.0.199.0](https://github.com/PCIT-Project/PCIT-CPP/blob/main/CHANGELOG.md#v0.0.199.0)


<!---------------------------------->
<a name="v0.0.11.0"></a>
## v0.0.11.0
- Made `bit.bitCast` always unsafe


<!---------------------------------->
<a name="v0.0.10.0"></a>
## v0.0.10.0
- Added checking of types in `bit.bitCast` to see if it should be unsafe


<!---------------------------------->
<a name="v0.0.9.0"></a>
## v0.0.9.0
- Added `#unsafe` to `bit.bitCast`


<!---------------------------------->
<a name="v0.0.8.0"></a>
## v0.0.8.0
- Added `bit` module
	- Added `bit.bitCast()`
- Added `types` module
	- Added `bit.numBytes()`
	- Added `bit.numBits()`
- Updated compiler-rt iterators to reflect updates to [PCIT-CPP v0.0.203.0](https://github.com/PCIT-Project/PCIT-CPP/blob/main/CHANGELOG.md#v0.0.203.0)


<!---------------------------------->
<a name="v0.0.7.0"></a>
## v0.0.7.0
- Updated compiler-rt iterators to reflect updates to [PCIT-CPP v0.0.202.0](https://github.com/PCIT-Project/PCIT-CPP/blob/main/CHANGELOG.md#v0.0.202.0)


<!---------------------------------->
<a name="v0.0.6.0"></a>
## v0.0.6.0
- Updated compiler-rt iterators to reflect updates to [PCIT-CPP v0.0.199.0](https://github.com/PCIT-Project/PCIT-CPP/blob/main/CHANGELOG.md#v0.0.199.0)


<!---------------------------------->
<a name="v0.0.5.0"></a>
## v0.0.5.0
- Added compiler-rt for iterators


<!---------------------------------->
<a name="v0.0.4.0"></a>
## v0.0.4.0
- Moved `build.Output` to an actual enum
- Removed `build.Output.BUILD_SYMBOL_PROCS`


<!---------------------------------->
<a name="v0.0.3.0"></a>
## v0.0.3.0
- Added more output targets
	- OBJECT
	- CONSOLE_EXECUTABLE
	- WINDOWED_EXECUTABLE


<!---------------------------------->
<a name="v0.0.2.0"></a>
## v0.0.2.0
- Changed license to BSD 1-Clause with PCIT Exceptions


<!---------------------------------->
<a name="v0.0.1.0"></a>
## v0.0.1.0
- Added std from [PCIT-CPP v0.0.112.0](https://github.com/PCIT-Project/PCIT-CPP/blob/main/CHANGELOG.md#v0.0.112.0)
	- Headers were modified to reflect the license


<!---------------------------------->
<a name="v0.0.0.0"></a>
## v0.0.0.0
- Initial commit