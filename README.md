<div align="center">

# Sasha test Kernels for Android devices running 6.1 


</div>

> [!CAUTION]
> Sasha Kernels is not responsible for bricked devices or damage. By flashing, you assume all risk. Back up your data and understand the risks before flashing.

---

## About

Generic kernels built on [Google's GKI sources](https://android.googlesource.com/kernel/common/) with KernelSU and SUSFS for root hiding and detection evasion — broad compatibility, not guaranteed for every device.

---

## Features

- **KernelSU-Next** — root implementation
- **susfs4ksu** — root hiding (incl. Ptrace Leak Fix, Unicode Fix)
- **NoMount / Mountify** — mount metamodules
- **Baseband Guard** — partition protection
- **Networking** — WireGuard, BBR, IPSet, CIFS
- **TMPFS** — xattr / POSIX ACLs
- **BPF** — BTF / eBPF / FUSE-BPF
- **Performance** — incl. NTSync
- **DroidSpaces** — container runtime
  
---

## Build Your Own Kernel

Fork the repository and follow **[Build Your Own Kernel](docs/build-from-fork.md)** to select one kernel family, patch level, root implementation, and feature set in GitHub Actions.

---

## Installation

See **[Installation Guide](https://github.com/WildKernels/GKI_KernelSU_SUSFS/wiki/Installation)**.

---



## Special Thanks

**These amazing people and projects make this possible:**

- **KernelSU** — [tiann](https://github.com/tiann/KernelSU)
- **KernelSU-Next** — [rifsxd](https://github.com/KernelSU-Next/KernelSU-Next)
- **KernelSU-Next SUSFS Fork** — [pershoot](https://github.com/pershoot/KernelSU-Next)
- **ReSukiSU** — [ReSukiSU](https://github.com/ReSukiSU/ReSukiSU)
- **Magic-KSU** — [5ec1cff](https://github.com/5ec1cff/KernelSU)
- **SUSFS** — [simonpunk](https://gitlab.com/simonpunk/susfs4ksu)
- **SUSFS Module** — [sidex15](https://github.com/sidex15)
- **NoMount** — [maxsteeel](https://github.com/maxsteeel/nomount)
- **DroidSpaces-OSS** — [ravindu644](https://github.com/ravindu644/Droidspaces-OSS)
- **Baseband-guard (BBG)** — [vc-teahouse](https://github.com/vc-teahouse/Baseband-guard)
- **Kernel Patches** — [WildKernels/kernel_patches](https://github.com/WildKernels/kernel_patches)
- **AnyKernel3** — [osm0sis](https://github.com/osm0sis/AnyKernel3)
- **Sultan Kernels (Pixel)** — [kerneltoast](https://github.com/kerneltoast)
- **Device Boot Fix** — [Boot fix commit](https://github.com/Anything-at-25-00/android_kernel_common_android12-5.10/commit/2476d262b597fe8af82cfb7aaf96676f51c6b4ed)


Have an idea or improvement in mind? Contributions are always welcome — feel free to open a pull request or share your thoughts!
