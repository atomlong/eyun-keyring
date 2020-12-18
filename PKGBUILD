# Maintainer: Atom Long <atom.long@hotmail.com>

pkgname=eyun-keyring
pkgver=20201203
pkgrel=1
pkgdesc='Arch linux ARM eyun PGP keyring'
arch=('any')
url='https://github.com/atomlong/eyun-keyring'
license=('GPL')
install="${pkgname}.install"
source=("https://github.com/atomlong/eyun-keyring/archive/${pkgver}.tar.gz")
sha256sums=('debbf16925ada76a908d8a362411daeb1f1f71331091ec238e2dc39cf3341009')

package() {
  cd "eyun-keyring-${pkgver}"
  make PREFIX=/usr DESTDIR=${pkgdir} install
}
