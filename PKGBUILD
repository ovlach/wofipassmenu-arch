# Maintainer: Ondrej Vlach <ondrej@vlach.xyz>

pkgname=wofipassmenu
pkgver=0.0.1
pkgrel=1
pkgdesc="Wofi based implementation of passmenu"
arch=('any')
url='https://github.com/ovlach/wofipassmenu'
license=('GPLv2')
depends=(pass wofi bash)
makedepends=()
provides=('wofipassmenu')
conflicts=('wofipassmenu')
source=('https://github.com/ovlach/wofipassmenu/archive/v0.0.1.tar.gz')
md5sums=('fca6d2cbff21cf63bfccdf53fa487fca')

package() {
	  cd "$srcdir"
	  install -Dm0755 "$srcdir/$pkgname-$pkgver/wofipassmenu" "$pkgdir/usr/bin/wofipassmenu"
}
