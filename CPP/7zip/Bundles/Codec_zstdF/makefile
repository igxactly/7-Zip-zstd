PROG = zstd.dll
DEF_FILE = ../../Compress/Codec.def
CFLAGS = $(CFLAGS) -DNEED_7ZIP_GUID -DZSTD_LEGACY_SUPPORT

7ZIP_COMMON_OBJS = \
  $O\StreamUtils.obj \

WIN_OBJS = \
  $O\System.obj \

COMPRESS_OBJS = \
  $O\CodecExports.obj \
  $O\DllExportsCompress.obj \

C_OBJS = \
  $O\Alloc.obj \
  $O\Threads.obj \

COMPRESS_OBJS = $(COMPRESS_OBJS) \
  $O\ZstdDecoder.obj \
  $O\ZstdEncoder.obj \
  $O\ZstdRegister.obj \

ZSTD_OBJS = \
  $O\xxhash.obj \
  $O\entropy_common.obj \
  $O\fse_decompress.obj \
  $O\huf_decompress.obj \
  $O\zstd_common.obj \
  $O\zstd_decompress.obj \
  $O\fse_compress.obj \
  $O\huf_compress.obj \
  $O\zstd_compress.obj \
  $O\zstdmt_compress.obj \
  $O\pool.obj \
  $O\error_private.obj \
  $O\zstd_v01.obj \
  $O\zstd_v02.obj \
  $O\zstd_v03.obj \
  $O\zstd_v04.obj \
  $O\zstd_v05.obj \
  $O\zstd_v06.obj \
  $O\zstd_v07.obj \

ZSTDMT_OBJS = \
  $O\threading.obj \
  $O\zstd-mt_common.obj \
  $O\zstd-mt_compress.obj \
  $O\zstd-mt_decompress.obj \

!include "../../7zip.mak"
