# Maintainer: mb6ockatf <mdddmmmm@yandex.ru>
# Contributor: mb6ockatf <github.com/mb6ockatf>

pkgname=fortune-mod-fightclub
pkgver=1
pkgrel=1
pkgdesc="#fightclub fortune cookie file"
arch=('any')
license=('AGPL-3.0-or-later')
url="https://github.com/mb6ockatf"
depends=('fortune-mod')
groups=('fortune-mods')
source=('fightclub')
sha256sums=('c59035429032d4063b34dd2d6a2edebab7fd8ff23671b433fe55fd874bdc2b75')

build() {
	strfile ${srcdir}/fightclub ${srcdir}/fightclub.dat
}

package() {
	  install -D -m644 ${srcdir}/fightclub ${pkgdir}/usr/share/fortune/fightclub
	  install -D -m644 ${srcdir}/fightclub.dat ${pkgdir}/usr/share/fortune/fightclub.dat
}
