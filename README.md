# go-awesome-simd
A curated list of awesome SimD GO code
### proposal: add package for using SIMD instructions [#53171](https://github.com/golang/go/issues/53171)
> [GopherCon 2019: Michael McLoughlin - Better x86 Assembly Generation from Go](https://www.youtube.com/watch?v=WaD8sNqroAw)
> [High performance scaling techniques in Go](https://www.youtube.com/watch?v=HdDOnJKyjhc)
> [Understanding the Go compiler](https://www.youtube.com/watch?v=qnmoAA0WRgE)
> [AVO - Generate x86 Assembly with Go](https://github.com/mmcloughlin/avo)
> [From slow to SIMD: A Go optimization story](https://sourcegraph.com/blog/slow-to-simd)
> [Accelerating SHA256 by 100x in Golang on ARM](https://blog.min.io/accelerating-sha256-by-100x-in-golang-on-arm/)
> [Optimizing Go programs by AVX2 using Auto-Vectorization in LLVM](https://c-bata.medium.com/optimizing-go-by-avx2-using-auto-vectorization-in-llvm-118f7b366969)
> [https://blog.yiningkarlli.com/2021/09/neon-vs-sse.html](https://blog.yiningkarlli.com/2021/09/neon-vs-sse.html)
### awesome implementations
> https://github.com/google/highway
> https://github.com/octu0/go-intrin
> https://github.com/mengzhuo/intrinsic
> https://github.com/zchee/go-simdutf
> [SimD HighwayHash](https://github.com/minio/highwayhash)
> [SimD accelerated search routines](https://github.com/jeschkies/go-memmem)
> [Stream VByte SimD](https://github.com/thempatel/streamvbyte-simdgo)
> [Stream VByte integer compression](https://github.com/rleiwang/svb)
> https://github.com/minio/c2goasm
> [minio JSON-SimD](https://github.com/minio/simdjson-go)
> [minio CSV-SimD](https://github.com/minio/simdcsv)
> [minio SHA256-SimD](https://github.com/minio/sha256-simd)
> [minio BLAKE2b-SimD](https://github.com/minio/blake2b-simd)
> [xxhash3](https://github.com/zchee/xxhash3)
> [MAGIC Algorithms go-swar](https://github.com/pennello/go_swar)
> [Go compiler intrinsics](https://github.com/Clement-Jean/simd-go-POC)
> [GenSimd](https://github.com/bjwbell/gensimd)
> https://github.com/racerxdl/segdsp-sample
> https://github.com/fwessels/go-cv
> [SimD for Go](https://github.com/yesuu/simd)
> [SimD XOR](https://github.com/templexxx/xorsimd)
> [SimD Bitwise AND](https://github.com/shenwei356/pand)
> [SimD DOT product](https://github.com/camdencheek/simd_blog/blob/main/dot_arm64.s)
> [SimD hashmap](https://github.com/jakobgt/cay)
> [SimD matrix math lib](https://github.com/silversquirl/matrix)
> [float64 SimD](https://github.com/xxgreg/floats)
> [float64x4 vectors](https://github.com/reiver/go-float64x4/blob/master/lanes.go)
> [float32 matrix and vector math lib](https://github.com/rkusa/gm)
> [Base64 SimD](https://github.com/emmansun/base64)
> [Hex encoding SimD](https://github.com/templexxx/xhex/blob/master/xhex_amd64.s)
> [SimD math lib bindings yeppp](https://github.com/vpxyz/goyeppp)
### assembly goodies
> [Plan9 assembly reference](https://www.quasilyte.dev/blog/post/go-asm-complementary-reference/)
>[Erasure coding](https://github.com/klauspost/reedsolomon)
>[SimD-Vectorized Bitmap (Bitset)](https://github.com/kelindar/bitmap)
>[X86 instruction set](https://www.felixcloutier.com/x86/index.html)
> [ARM64 Instruction set](https://dougallj.github.io/asil/)
> [ARM64 Go support](https://pkg.go.dev/cmd/internal/obj/arm64)
> [Go ARM64 test data](https://github.com/golang/go/blob/master/src/cmd/asm/internal/asm/testdata/arm64enc.s)
> [isAlphaNumeric arm64](https://github.com/felixge/isalphanumeric/blob/main/isalphanumeric_arm64.s)
> [AVX Instruction set](https://gist.github.com/alexcrichton/3281adb58af7f465cebee49759ae3164)
> [AVX 512 Go support](https://go.dev/wiki/AVX512)
> [Go AVX512 test data](https://github.com/golang/go/tree/master/src/cmd/asm/internal/asm/testdata/avx512enc)
> [Go sneller AVX512](https://github.com/SnellerInc/sneller)
> [Go AVX512 md5](https://github.com/minio/md5-simd)

### rustafarians 
>[Rust: faster](https://github.com/AdamNiederer/faster)
