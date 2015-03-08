# Maintainer: Augusto Hack <hack.augusto@gmail.com>
pkgname=tinyrocket
pkgver=1
pkgrel=1
pkgdesc="Application Container Image generator"
arch=('x86_64')
license=('GPL')
depends=('zsh' 'pacman' 'systemd')
source=('tinyrocket')
md5sums=('4b1dbb383b9722bb035c48d8159bce9c')

package() {
    install -D -m755 "$srcdir/tinyrocket" "$pkgdir/usr/bin/tinyrocket"
}
