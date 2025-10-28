_pkgname=pack
pkgname=$_pkgname
pkgver=1.1.0
pkgrel=1
pkgdesc="Simple yet powerful AUR Helper TUI"
arch=('x86_64')
license=('GPL3')
depends=('bash' 'fzf' 'expac' 'gum')
makedepends=('curl')
optdepends=('paru: AUR support' 'yay: AUR support')

source=(
  "https://raw.githubusercontent.com/elrondforwin/pack/refs/heads/master/pack"
  "https://raw.githubusercontent.com/elrondforwin/pack/refs/heads/master/pack.desktop"
)

sha256sums=(
  'SKIP'
  'SKIP'
)

package() {
  install -Dm755 "$srcdir/pack" "$pkgdir/usr/bin/pack"

  install -Dm644 "$srcdir/pack.desktop" "$pkgdir/usr/share/applications/pack.desktop"

}
