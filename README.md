# Warehouse Fix

A fix for the leJOS rp.robotics.mapping.MapUtils createRealWarehouse2016 function from the [rp-shared][1] project that prevents robots from getting stuck when trying to rotate in certain positions.

This project is intended to exist while the pull request is being processed for the original project. It may be removed if the pull request is approved.

## Getting Started

Import into a project using the [rp-shared][1] project. Instead of calling `MapUtils.createRealWarehouse()` instead call `MapUtilsFix.createRealWarehouse2018()`.

## Author

* [rp-utils by hawesie][1]

* Fix by Philip Eagles

## License

This project is licensed under the MIT License - see the [LICENSE.md][2] file for details.

[1]: https://github.com/hawesie/rp-shared
[2]: https://github.com/corfeur12/warehouse_MapUtils_fix/blob/master/LICENSE
