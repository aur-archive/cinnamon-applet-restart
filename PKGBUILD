# Contributor: gareth_c
# Maintainer: Ner0

pkgname=cinnamon-applet-restart
pkgver=1.02
pkgrel=1
pkgdesc="Simply restart Cinnamon with one click."
arch=('any')
url="http://cinnamon-spices.linuxmint.com/applets/view/14"
license=('GPL')
groups=('cinnamon-applets')
depends=('cinnamon')
source=('http://cinnamon-spices.linuxmint.com/uploads/applets/V3Z6-QFO8-4RVI.zip')
md5sums=('1827b2724ed40cee79015ef09fb0161b')

package() {
  find restart-cinnamon\@kolle/ -type f -exec install -Dm644 '{}' "$pkgdir/usr/share/cinnamon/applets/{}" \;
}
