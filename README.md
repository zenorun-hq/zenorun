# Zenorun

Self-hosted runners for GitHub Actions jobs, each in a fresh KVM virtual machine on your own server.

Zenorun is not released yet. Join the waitlist at [zenorun.com](https://zenorun.com). The install files, release notes and the README for installing Zenorun will be published here at launch.

## Source code of GPL components

EGR's public images (`ghcr.io/hexsis-llc/ephemeral-gh-runners` and `ghcr.io/hexsis-llc/ephemeral-kvm-runner`) contain software under the GNU General Public License (GPL) and the GNU Lesser General Public License (LGPL). Among them are QEMU, the Linux kernel and other Ubuntu packages in the runner images, and Alpine packages such as busybox and xfsprogs in the service image. For at least three years after we last distribute a given version of an image, Hexsis Enterprise LLC will give anyone who asks a complete machine-readable copy of the corresponding source code of every GPL or LGPL component in that version, for no more than our cost of physically performing the distribution. This covers every version of these packages, including those published before the images carried this offer. To ask, write to legal@zenorun.com or Hexsis Enterprise LLC, 542 Washington Ave 18, Miami Beach, FL 33139, USA, and name the image and its digest (`sha256:…`).

© Hexsis Enterprise LLC
