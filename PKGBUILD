pkgname=print-iommu
pkgver=1.0 
pkgrel=1
pkgdesc="Prints iommu groups, created by @r15ch13" 
arch=('x86_64')
url=TBD
license=('GPL')
source=("git+https://gist.github.com/40dc881248c5685d1b9ccfbf559269fa.git")
sha256sums=('SKIP')

build() {
    cd "$srcdir"
    mv 40dc881248c5685d1b9ccfbf559269fa/iommu.sh print-iommu 
}

package() {
    cd "$srcdir"
    install -Dm755 print-iommu "$pkgdir/usr/bin/print-iommu" 
}

