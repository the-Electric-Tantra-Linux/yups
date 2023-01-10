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
sha256sums=('d7f547406531eb8429796fea7db26df816f751e2dbfaa23de334fe66399dd803')

package() {
  install -Dm775 "$srcdir/$pkgname-$pkgver/yups" "$pkgdir/usr/bin/yups"
  install -Dm775 "$srcdir/$pkgname-$pkgver/yups-query" "$pkgdir/usr/bin/yups-query"
}
