# Maintainer: webdawg
pkgname=aur-safe-update-manual
pkgver=1.0.0
pkgrel=2
pkgdesc='Manual AURWatch safety check for installed AUR upgrades'
arch=('any')
url='https://github.com/webdawg/aur-safe-update'
license=('MIT')
depends=('bash' 'coreutils' 'curl' 'jq' 'pacman')
source=('aur-safe-update-manual')
sha256sums=('SKIP')

package() {
    install -Dm755 "$srcdir/aur-safe-update-manual" \
        "$pkgdir/usr/bin/aur-safe-update-manual"
}
