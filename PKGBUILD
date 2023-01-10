# Maintainer: Niklas Adam <salkinmada@protonmail.com>
pkgname=yups
pkgver=1.0.0
pkgrel=1
pkgdesc="A fzf TUI for paru"
arch=("any")
url="https://github.com/the-Electric-Tantra-Linux/yups"
license=("GPL3")
depends=("fzf" "paru" "bash" )
source=("$pkgname-$pkgver.tar.gz::$url/archive/refs/tags/$pkgver.tar.gz")
sha256sums=('f16960f308aac1f1e16660194eb3381b60d3b9d6784a2b8a7f64831e5a72f7c0')

package() {
  install -Dm775 "$srcdir/$pkgname-$pkgver/yups" "$pkgdir/usr/bin/yups"
  install -Dm775 "$srcdir/$pkgname-$pkgver/yups-query" "$pkgdir/usr/bin/yups-query"
}
