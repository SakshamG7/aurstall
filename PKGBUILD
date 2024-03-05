# Maintainer: Saksham Goel <mail@sakshamg.com>

pkgname='aurstall'
pkgver='1'
pkgrel=1
pkgdesc="Single Command Installation Tool For AUR Packages"
arch=('x86_64')
license=('GPL')
depends=('base-devel' 'git')
# makedepends=()
url="https://github.com/SakshamG7/aurstall"
source=()
md5sums=()

prepare() {
  # clone the repository if src/aurstall doesn't exist
  if [ ! -d "${srcdir}/aurstall" ]; then
    git clone https://github.com/SakshamG7/aurstall.git ./
  fi
}

package() {
  # install script
  install -D -m755 "${srcdir}/aurstall" "${pkgdir}/usr/bin/aurstall"
}
