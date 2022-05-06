# OpenSSL 1.1.1o x64

# Put the next variables of Environment, and add the folders to path, you can skip however data and private subfolders inside SSL folder.

# Each variable is named different and should be like this:

# OPENSSLDIR with the path: C:\Program Files\Common Files\SSL\
# ENGINESDIR with the path: C:\Program Files\OpenSSL\lib\engines-1_1\
# MODULESDIR with the path: C:\Program Files\OpenSSL\lib\ossl-modules\

# Now point directly in Path, and point to these folders:

# C:\Program Files\OpenSSL\lib\engines-1_1\
# C:\Program Files\OpenSSL\lib\ossl-modules\
# C:\Program Files\Common Files\SSL\data\
# C:\Program Files\Common Files\SSL\certs\
# C:\Program Files\Common Files\SSL\misc\
# C:\Program Files\Common Files\SSL\private\
# C:\Program Files\OpenSSL\bin\

# Reboot your computer, or get chocolatey and perform the next command: refreshenv.
# Inside the data folder should be the certificates or however You want to link them.
# As well private folder for private keys such as SSH protocol ones. Or certificates.
# To re-check as well on command line after this, type: openssl version -a

# If this is the output You did everything good.

# C:\Users\>openssl
# OpenSSL> version -a
# OpenSSL 1.1.1o  3 May 2022
# built on: Fri May  6 07:38:06 2022 UTC
# platform: VC-WIN64A-masm
# options:  bn(64,64) rc4(16x,int) des(long) idea(int) blowfish(ptr)
# compiler: cl /Zi /Fdossl_static.pdb /Gs0 /GF /Gy /MD /W3 /wd4090 /nologo /O2 -DL_ENDIAN -DOPENSSL_PIC -DOPENSSL_CPUID_OBJ -DOPENSSL_IA32_SSE2 -DOPENSSL_BN_ASM_MONT -DOPENSSL_BN_ASM_MONT5 -DOPENSSL_BN_ASM_GF2m -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DKECCAK1600_ASM -DRC4_ASM -DMD5_ASM -DAESNI_ASM -DVPAES_ASM -DGHASH_ASM -DECP_NISTZ256_ASM -DX25519_ASM -DPOLY1305_ASM
# OPENSSLDIR: "C:\Program Files\Common Files\SSL"
# ENGINESDIR: "C:\Program Files\OpenSSL\lib\engines-1_1"
# Seeding source: os-specific

# If the version says OpenSSL 1.1.1o x64, you did all the steps well.
# Those are the ones that should be kept at first, in case You need this version, pull them over to the top, to avoid any other version from getting in the way.
# That should do it. It as well, includes all the documentation of this version of OpenSSL.

# Compilation done by: Fernando O.
# 06/05/2022
