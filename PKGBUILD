# Maintainer: Your Name <your-email@example.com>
pkgname=funfetch
pkgver=1.0.0
pkgrel=1
pkgdesc="A simple and fun system fetch utility with an ASCII smile"
arch=('any')
url="https://github.com"
license=('MIT')
depends=('bash' 'util-linux' 'pciutils' 'procps-ng')
source=("funfetch")
sha256sums=('SKIP')

package() {
    install -Dm755 "${srcdir}/funfetch" "${pkgdir}/usr/bin/funfetch"
}
