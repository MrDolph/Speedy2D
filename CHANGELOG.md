## 1.0.0

* Initial release

## 1.0.1

* Fixed issue when deleting a texture while binding a new one

## 1.0.2

* Fixed build issue when using without windowing enabled

## 1.0.3

* Fixed negative overflow issue where monitor size is misdetected or less than window size

## 1.0.4

* No longer specifies core profile for GL 2.0 (fixes issue on Macs)

## 1.0.5

* Setting multisampling level to 16 by default

## 1.0.6

* Ensure event loop gets woken up when redrawing on Windows

## 1.0.7

* Fix error on some platforms due to GL shader program validation

## 1.1.0

### New APIs

* `WindowCreationOptions::with_resizable()`
* `WindowCreationOptions::with_always_on_top()`
* `WindowCreationOptions::with_maximized()`
* `WindowCreationOptions::with_decorations()`
* `Graphics2D::create_image_from_file_path()`
* `Graphics2D::create_image_from_file_bytes()`
* `GLRenderer::create_image_from_file_path()`
* `GLRenderer::create_image_from_file_bytes()`

### Other changes

* `Graphics2D::draw_image()` is now able to take a tuple as a position