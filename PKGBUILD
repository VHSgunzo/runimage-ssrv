# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='runimage-ssrv'
pkgver='0.3.2'
pkgrel='1'
pkgdesc='ssrv for RunImage container'
url='https://github.com/VHSgunzo/ssrv'
arch=('x86_64' 'aarch64')
license=('MIT')
options=(!strip)
provides=("ssrv=$pkgver-$pkgrel")
depends=('runimage-static')
source=("$url/releases/download/v$pkgver/ssrv-${CARCH}-v$pkgver.r0.gfebc9d3.tar.zst")
sha256sums=('SKIP')

package() {
  install -Dm755 "ssrv" "${pkgdir}/var/RunDir/sharun/bin/ssrv"
}
