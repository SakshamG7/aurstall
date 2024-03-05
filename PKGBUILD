# Maintainer: Saksham Goel <mail@sakshamg.com>

pkgname='aurstall'
pkgver='1'
pkgrel=1
pkgdesc="Single Command Installation Tool For AUR Packages"
arch=('x86_64')
license=('GPL')
depends=('base-devel')
makedepends=('git')
url="https://github.com/SakshamG7/aurstall"
source=("https://github.com/SakshamG7/aurstall/$pkgname-$pkgver.tar.gz")
md5sums=('SKIP')

package() {
  # install script
  install -D -m755 "${srcdir}/aurstall" "${pkgdir}/usr/bin/aurstall"
}
