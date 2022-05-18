# v0.6.0
- Fixed `Bimage_display.Window.mouse_position`
- Link against `libOpenImageIO_Util`
- Added `Expr.prepare`

# v0.5.0
- Removed `Bimage_unix.Thread.Filter`
- Renamed `Bimage_unix.{Data_unix,Image_unix}.create_mmap` to `mmap`
- Removed `Filter.Make`, `FILTER` and `bimage-lwt`

# v0.4
- Added `let*` and `let+` operators
- Added `Window.window`
- Fix type in `Bimage_display`

# v0.3.1
- More aggressive image type checking in `bimage-display` to fix possible
  segmentation faults

# v0.3.0
- Overhaul of `Color` and `Type`
- Added `FILTER`/`Filter`
- Added `Bimage_io` and `Bimage_lwt`

# v0.2.1
- Add Func Expr
- Rewrite ops as exprs
- Update stb-image/stb-image-write

# v0.1.1
- Update to GTK3
- Fix tests and examples
