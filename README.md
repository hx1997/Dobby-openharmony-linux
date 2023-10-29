This is Dobby ported to OpenHarmony. To build, run this on Windows:

```bash
python scripts\platform_builder.py --platform=openharmony --arch=arm64 --cmake_dir=%OHOS_NDK_HOME%\build-tools\cmake --llvm_dir=C:\\Users\\<用户名>\\AppData\\Local\\Huawei\\Sdk\\openharmony\\9\\native\\llvm
```

where `%OHOS_NDK_HOME%` is the path to your OpenHarmony NDK (e.g., `%LOCALAPPDATA%\\Huawei\\Sdk\\openharmony\\9\\native`).

## Dobby

[![Contact me Telegram](https://img.shields.io/badge/Contact%20me-Telegram-blue.svg)](https://t.me/IOFramebuffer) [![Join group Telegram](https://img.shields.io/badge/Join%20group-Telegram-brightgreen.svg)](https://t.me/dobby_group)

Dobby a lightweight, multi-platform, multi-architecture exploit hook framework.

- Minimal and modular library
- Multi-platform support(Windows/macOS/iOS/Android/Linux)
- Multiple architecture support(X86, X86-64, ARM, ARM64)

## Compile

[docs/compile.md](docs/compile.md)

## Download

[download latest library](releases/tag/latest)

## Credits

1. [frida-gum](https://github.com/frida/frida-gum)
2. [minhook](https://github.com/TsudaKageyu/minhook)
3. [substrate](https://github.com/jevinskie/substrate).
4. [v8](https://github.com/v8/v8)
5. [dart](https://github.com/dart-lang/sdk)
6. [vixl](https://git.linaro.org/arm/vixl.git)
