# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=binutils-h8300-hms
pkgver=2.16.1
pkgrel=1
pkgdesc="h8300 cross binutils"
arch=('x86_64')
url=""
license=('GPL')
groups=()
depends=()
makedepends=()
install=
source=("binutils-h8300-hms.deb::http://ftp.jp.debian.org/debian/pool/main/b/binutils-h8300-hms/binutils-h8300-hms_2.16.1-10+b2_amd64.deb")
md5sums=("fdac01f140b0b5bcb434b06eba9a1d70")

package() {
	bsdtar -xf data.tar.xz -C "$pkgdir/"
}
