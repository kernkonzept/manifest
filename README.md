# L4Re manifest

This package contains the ham manifest which can be used to checkout and manage
the L4Re operating system git repositories.

## The L4Re Operating System

The L4Re Runtime Environment is an operating system framework for building
systems with real-time, security, safety and virtualization requirements. It
consists of the [L4Re hypervisor/kernel](https://l4re.org/fiasco/) and a
user-level infrastructure that includes basic services such as program loading
and memory management. L4Re also provides the environment for applications,
including libraries and process-local functionality.

## Build

Please see our detailed instructions on [how to build](BUILDING) L4Re using the
manifest in this repo.

## Tutorials

  * [Building L4Re](https://github.com/kernkonzept/manifest/wiki/BUILDING)
  * [Running a Linux guest VM](https://github.com/kernkonzept/manifest/wiki/LinuxVM)
  * [Running multiple Linux guest VMs](https://github.com/kernkonzept/manifest/wiki/MultipleVMs)
  * [Hardware pass-through to the VM](https://github.com/kernkonzept/manifest/wiki/NVMeWithLinux)
  * [Using the NVMe server with a Linux guest VM](https://github.com/kernkonzept/manifest/wiki/NVMeWithLinux)
  * [Demo of the L4Re Micro Hypervisor for MPU-based systems](https://github.com/kernkonzept/demo-l4re-micro-hypervisor)

## Contribute

We welcome contributions to L4Re. Please see our contributors guide on [how to
contribute](CONTRIBUTING).

## License

The L4Re manifest is licensed under GPL-2.0-only unless you have received this
package under a different license from Kernkonzept. The other L4Re repositories
contain a LICENSE.spdx file with detailed license information. For more
information please contact us at **info@kernkonzept.com**.
