# Change Log

<!---------------------------------->
<a name="v0.0.38.0"></a>
## v0.0.38.0
- Added `bit.bitFloor()`
- Added `bit.bitCeil()`
- Added `bit.bitReverse()`
- Added `bit.bitWidth()`
- Added `bit.byteSwap()`
- Added `bit.countLZero()`
- Added `bit.countRZero()`
- Added `bit.countLOne()`
- Added `bit.countROne()`


<!---------------------------------->
<a name="v0.0.37.0"></a>
## v0.0.37.0
- Added `@setModuleName()` to every file


<!---------------------------------->
<a name="v0.0.36.0"></a>
## v0.0.36.0
- Added full implementation for `__chkstk`


<!---------------------------------->
<a name="v0.0.35.0"></a>
## v0.0.35.0
- Added `rangeFor`
- Added `reverseRangeFor`
- Fixed `math.ceilToPowOf2Multiple()`, `math.ceilToMultiple()`, `math.floorToPowOf2Multiple()`, and `math.floorToMultiple()` rounding the wrong direction for negative numbers


<!---------------------------------->
<a name="v0.0.34.0"></a>
## v0.0.34.0
- Added `heap` module
	- `heap.PageAllocator`
	- `heap.pageSize()`
- Added `mem.Allocator`
- Added `mem.IAllocator`
- Added `mem.createAllocator()`
- Added `mem.createPmAllocator()`
- Added `bit.popCount()`
- Added `math.isPowOf2()`
- Added `math.ceilToPowOf2Multiple()`
- Added `math.ceilToMultiple()`
- Added `math.floorToPowOf2Multiple()`
- Added `math.floorToMultiple()`


<!---------------------------------->
<a name="v0.0.33.0"></a>
## v0.0.33.0
- Added `Atomic`
- Added `AtomicRef`
- Added `AtomicOrdering`
- Added `StaticArrayList`


<!---------------------------------->
<a name="v0.0.32.0"></a>
## v0.0.32.0
- Removed `inPanicHandler`
- Updated to use `@config.mode` instead of `@config.includeDebugInfo`
- Improved `assert` to allow continued execution when a debugger is attached


<!---------------------------------->
<a name="v0.0.31.1"></a>
## v0.0.31.1
- Fixed `debug.print` and `debug.println` in runtime on Windows


<!---------------------------------->
<a name="v0.0.31.0"></a>
## v0.0.31.0
- Added `os.windows.HeapAllocFlags`
- Added `os.windows.HeapFreeFlags`
- Added delete messages for os modules


<!---------------------------------->
<a name="v0.0.30.0"></a>
## v0.0.30.0
- Added `os.linux`
	- `exit`
	- `write`


<!---------------------------------->
<a name="v0.0.29.0"></a>
## v0.0.29.0
- Added comptime printing to `debug.print` and `debug.println`


<!---------------------------------->
<a name="v0.0.28.0"></a>
## v0.0.28.0
- Added entry to compiler-rt
- Added `debug.println`
- Added to `os.windows`
	- `exitProcess`
	- `getProcessHeap`
	- `heapAlloc`
	- `heapFree`
- Fixed `debug.print` not working when in panic handler


<!---------------------------------->
<a name="v0.0.27.0"></a>
## v0.0.27.0
- Added `types.isRuntimeDefaultInitializable`
- Added `types.isRuntimeDeletable`
- Added `types.isRuntimeCopyable`
- Added `types.isRuntimeMovable`
- Added `types.isRuntimeComparable`


<!---------------------------------->
<a name="v0.0.26.0"></a>
## v0.0.26.0
- Added `os` module
- Added `os.windows` module
	- `Handle`
	- `StdHandle`
	- `getLastError`
	- `getStdHandle`
	- `outputDebugStringA`
	- `writeConsoleA`
	- `writeFile`
- Added `inPanicHandler`
- Added builtins
	- Added CallingConvention
	- Added Language
	- Added Architecture
	- Added Platform
	- Added Mode
	- Added OptMode
	- Added iteration types such as `Iterable` and `MutIteratorRT`
- Made `debug.assert` be a no-op when not including debug info


<!---------------------------------->
<a name="v0.0.25.2"></a>
## v0.0.25.2
- Fixed `__chkstk` having the wrong calling convention


<!---------------------------------->
<a name="v0.0.25.1"></a>
## v0.0.25.1
- Fixed alignment of `ManualLifetime`


<!---------------------------------->
<a name="v0.0.25.0"></a>
## v0.0.25.0
- Removed `build.Output`


<!---------------------------------->
<a name="v0.0.24.0"></a>
## v0.0.24.0
- Added to `types module`
	- Added `types.isIntegral()`
	- Added `types.isUnsignedIntegral()`
	- Added `types.isSignedIntegral()`
	- Added `types.isFloatingPoint()`
	- Added `types.isPointer()`


<!---------------------------------->
<a name="v0.0.23.0"></a>
## v0.0.23.0
- Renamed `asserts` module to `debug`
	- `std.assert` now must be `std.debug.assert`


<!---------------------------------->
<a name="v0.0.22.0"></a>
## v0.0.22.0
- Removed optional pointer overloads of `advancePointer` and `pointerDistance`
- Fixed `mem.moveBuffer` not having parameter `src` be a mut array reference


<!---------------------------------->
<a name="v0.0.21.0"></a>
## v0.0.21.0
- Added `__chkstk` to compiler_rt
- Renamed `incrementPointer` to `advancePointer`
- Removed `decrementPointer`


<!---------------------------------->
<a name="v0.0.20.0"></a>
## v0.0.20.0
- Added `ptrMath` module
	- Added `incrementPointer`
	- Added `decrementPointer`
	- Added `pointerDistance`


<!---------------------------------->
<a name="v0.0.19.0"></a>
## v0.0.19.0
- Updated `ManualLifetime` to reflect updates to [PCIT-CPP v0.0.248.0](https://github.com/PCIT-Project/PCIT-CPP/blob/main/CHANGELOG.md#v0.0.248.0)


<!---------------------------------->
<a name="v0.0.18.0"></a>
## v0.0.18.0
- Added `ManualLifetime`


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