## 2.1.0 - [14/12/2021]

* Deprecated `getImage`,  `getMultiImages` and `getVideo` methods.
* Added methods `getImageAsBytes`, `getImageAsWidget`, `getImageAsFile`, `getMultiImagesAsBytes`, `getMultiImagesAsWidget`, `getMultiImagesAsFile`,  `getVideoAsFile` and `getVideoAsBytes` ([#29](https://github.com/Ahmadre/image_picker_web/issues/29))

## 2.0.3+1 - [27/06/2021]

* Fixed a typo in the `README.md`

## 2.0.3 - [15/06/2021]

* Fixed issue [#25](https://github.com/Ahmadre/image_picker_web/issues/25) when clicking on cancel or close buttons
* Improved example file

## 2.0.2 - [27/04/2021]

* Fixed issue [#22](https://github.com/Ahmadre/image_picker_web/issues/22)

## 2.0.1 - [30/03/2021]

* Fixed `FutureOr<Map<String, dynamic>>` cast

## 2.0.0 - [27/03/2021]

* **Breaking Changes**: migrated code to nullsafety
* Removed deprecated properties

## 1.1.3 - [06/10/2020]

* Added `toJson` method to `MediaInfo`
* Fixed `getImageInfo` and `getVideoInfo`
* Updated `example/main.dart`

## 1.1.2+1 - [06/10/2020]

* Fixed `pickImage` and `pickVideo`

## 1.1.2 - [06/10/2020]

* Fixed compatibility with iOS web browser

## 1.1.1 - [02/10/2020]

* Upgraded minimum sdk to `>=2.7.0`
* Added new `ImageType.mediaInfo`
* Made some code refacto 

## 1.1.0+2 - [01/09/2020]

* Update README.md

## 1.1.0+1 - [01/09/2020]

* Format code to dartfm standard
* Added comments

## 1.1.0 - [01/09/2020]

* Retake of the discontinued package [image_picker_web](https://pub.dev/packages/image_picker_web)
* Refacto of method `getImage`
* Added method `getMultiImages` to allow multi-image selection
* Added a few comments for documentation generations
