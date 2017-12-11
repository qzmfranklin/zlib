licenses(['notice'])
package(default_visibility=['//visibility:public'])

cc_library(
    name = 'zlib',
    srcs = [
        'adler32.c',
        'compress.c',
        'crc32.c',
        'deflate.c',
        'infback.c',
        'inffast.c',
        'inflate.c',
        'inftrees.c',
        'trees.c',
        'uncompr.c',
        'zutil.c',
    ],
    hdrs = [
        'crc32.h',
        'deflate.h',
        'gzguts.h',
        'inffast.h',
        'inffixed.h',
        'inflate.h',
        'inftrees.h',
        'trees.h',
        'zconf.h',
        'zlib.h',
        'zutil.h',
    ],
    includes = [
        '.',
    ],
    linkstatic = 1,
)
