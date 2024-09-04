# Intel's libhoudini for intel/AMD x86 CPU, pulled from HPE image from Google Play Games for PC

`houdini` version: 14.0.0b_y.39441.g

`houdini64` version: 14.0.0b_z.39441.g

Android image fingerprint: google/kiwi_x86_64_dev/vsoc_kiwi_x86_64:14/UKW1.240818.001/12244619:user/release-keys

## How to include it in your Android-x86 build :
To include it, cherry-pick or make these commit as a reference:

https://github.com/supremegamers/device_generic_common/commit/e4f3b23aa2042a27607e31d15367978e0fae29a2

https://github.com/BlissRoms-x86/platform_device_generic_x86_64/commit/ef3fe8b00584eb60f6849d18cfc03a54e88901f7

Additionally, remove all the old nativebridge scripts/lib that was in Android-x86 in case you can't compile:

https://github.com/supremegamers/device_generic_common/commit/553b43cff47bb72dd712589a6744be8f173c9d8e

https://github.com/supremegamers/device_generic_common/commit/ae4cd3264d3e625d339e7cf9ae42821b51d55ade

