# Maintainer: McQueen <clear3239@yahoo.com>

pkgname=plank-theme-anti-shade
pkgver=0.1
pkgrel=1
arch=('any')
url='https://github.com/MMcQueenGNU/plank-theme-anti-shade'
license=('GPL3')
depends=('plank')
source=("git://github.com/MMcQueenGNU/$pkgname.git")
sha256sums=('SKIP')

build() {
	true
}

package() {
	cd $srcdir/$pkgname
	mkdir -p $pkgdir/usr/share/plank/themes/anti-shade
	install -m 755 dock.theme $pkgdir/usr/share/plank/themes/anti-shade/
}
