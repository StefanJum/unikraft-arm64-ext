## Steps to reproduce the issue

* The `.config` file is already provided, with just `BTE` enabled.
  The app also breaks for `PAuth`, `MTE` and `RNG`.
* Compile using the [linux toolchain](https://developer.arm.com/downloads/-/gnu-a).
* When running the app, it either hangs or catches a trap.
