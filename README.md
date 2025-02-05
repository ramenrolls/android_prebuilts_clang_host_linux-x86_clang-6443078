# README: Android Clang Toolchain (r383902)
This toolchain provides Clang 11.0.1 (based on r383902) for building `older` Linux kernels, particularly kernel version 4.19.

## Installation

Clone the repository
```bash
git clone prebuilts/clang/host/linux-x86/clang-r383902
```

## Directory Structure

The toolchain contains the following essential directories and files:

| Component | Purpose |
| --- | --- |
| bin/ | Executable binaries including clang compiler |
| include/ | Header files for compilation |
| lib64/ | Shared libraries |
| libexec/ | Runtime executables |
| python3/ | Python environment for toolchain utilities |
| runtimes_ndk_cxx/ | NDK C++ runtime support |
| share/ | Shared resources and documentation |
| test/ | Test suite for verification |
| AndroidVersion.txt | Toolchain version information |
| NOTICE | Legal notices and attributions |
| manifest_6443078.xml | Build configuration manifest |


- This toolchain is specifically designed for building Linux kernel versions compatible with Clang 11.0.1
- All necessary dependencies are included in the pre-built binaries

Important For optimal results, ensure your build environment matches the target kernel requirements
