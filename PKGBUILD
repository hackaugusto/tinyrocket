# Maintainer: Augusto Hack <hack.augusto@gmail.com>
pkgname=tinyrocket
pkgver=1
pkgrel=1
pkgdesc="Application Container Image generator"
arch=('x86_64')
license=('GPL')
depends=('zsh' 'pacman' 'systemd')
source=('tinyrocket' 'tinybuild')
md5sums=('b7ee13da56f4ef63f1a35b14601a3ac2'
         '249a6434e6c8472a2307f000a41ba410')

package() {
    install -D -m755 "$srcdir/tinyrocket" "$pkgdir/usr/bin/tinyrocket"
    install -D -m755 "$srcdir/tinybuild" "$pkgdir/usr/bin/tinybuild"
}
