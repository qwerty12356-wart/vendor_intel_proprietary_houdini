# Intel's libhoudini for intel/AMD x86 CPU, pulled from Tencent AoW Emulator

`houdini` version: 12.0.1.y.Tencent_AoW_Com5.9 (12.0.1_y.39067.m)

`houdini64` version: 12.0.1.z.Tencent_AoW_Com5.9 (12.0.1_z.39067.m)

Android image fingerprint: intel/caas/caas:12/SQ1A.220205.002/root12062147:user/release-keys

## How to include it in your Android-x86 build :
To include it, cherry-pick or make these commit as a reference:

https://github.com/supremegamers/device_generic_common/commit/e4f3b23aa2042a27607e31d15367978e0fae29a2

https://github.com/BlissRoms-x86/platform_device_generic_x86_64/commit/ef3fe8b00584eb60f6849d18cfc03a54e88901f7

Additionally, remove all the old nativebridge scripts/lib that was in Android-x86 in case you can't compile:

https://github.com/supremegamers/device_generic_common/commit/553b43cff47bb72dd712589a6744be8f173c9d8e

https://github.com/supremegamers/device_generic_common/commit/ae4cd3264d3e625d339e7cf9ae42821b51d55ade

