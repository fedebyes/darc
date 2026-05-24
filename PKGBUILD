# Maintainer: fedebyes <fedeb703@gmail.com>
pkgname=grub2-theme-dharma-arc
pkgver=1.0
pkgrel=1
pkgdesc="Dark GRUB2 theme based on Dharma, recolored for Arc Dark Gray KDE palette"
arch=('any')
url="https://github.com/fedebyes/grub2-theme-dharma-arc"
license=('CC-BY-SA')
depends=('grub')
source=("$pkgname-$pkgver.tar.gz::https://github.com/fedebyes/grub2-theme-dharma-arc/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('SKIP')

package() {
    install -dm755 "$pkgdir/usr/share/grub/themes/$pkgname"
    cp -r "$srcdir/$pkgname-$pkgver/dharma-arc/"* "$pkgdir/usr/share/grub/themes/$pkgname/"

    install -Dm644 "$srcdir/$pkgname-$pkgver/LICENSE" "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
