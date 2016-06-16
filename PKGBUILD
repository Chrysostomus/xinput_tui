# Maintainer: Chrysostomus @forum.manjaro.org

pkgname=xinput_tui
pkgver=0.1
pkgrel=1
pkgdesc="An interactive xinput interface using bash"
arch=(any)
url="https://github.com/Chrysostomus/$pkgname"
license=('MIT')
depends=('xorg-xinput'
	'awk'
	'bash')
makedepends=('git')
source=("git://github.com/Chrysostomus/$pkgname")
md5sums=('SKIP')

package () {
	cd "$srcdir"
        install -Dm755 "$srcdir/$pkgname/xinput-tui" "$pkgdir/usr/bin/"
}
