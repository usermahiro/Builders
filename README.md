# OrangeFox Action Builder
Compile your first custom recovery from OrangeFox Recovery using Github Action.

# How to Use
1. Fork this repository.

2. Go to `Action` tab > `All workflows` > `OrangeFox - Build` > `Run workflow`, then fill all the required information:
 * MANIFEST_BRANCH (`12.1` and `14.1`)
 * DEVICE_TREE ( your device tree repository link.)
 * DEVICE_TREE_BRANCH (Your device tree repository branch.)
 * DEVICE_PATH (`device/vendor/codename`)
 * DEVICE_NAME ( your codename)
 * BUILD_TARGET (`boot`, `recovery`, `vendorboot`)

