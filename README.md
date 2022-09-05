# armv5-buildroot
   
    make


# ExecutableFile

readelf -h executable_file


    ELF ヘッダ:
    マジック:  7f 45 4c 46 01 01 01 00 00 00 00 00 00 00 00 00 
    クラス:                            ELF32
    データ:                            2 の補数、リトルエンディアン
    Version:                           1 (current)
    OS/ABI:                            UNIX - System V
    ABI バージョン:                    0
    型:                                DYN (Position-Independent Executable file)
    マシン:                            ARM
    バージョン:                        0x1
    エントリポイントアドレス:          0x3bc
    プログラムヘッダ始点:            52 (バイト)
    セクションヘッダ始点:              6424 (バイト)
    フラグ:                            0x5000200, Version5 EABI, soft-float ABI
    Size of this header:               52 (bytes)
    Size of program headers:           32 (bytes)
    Number of program headers:         7
    Size of section headers:           40 (bytes)
    Number of section headers:         25
    Section header string table index: 24


file executable_file


   TypeDYN: ELF 32-bit LSB pie executable, ARM, EABI5 version 1 (SYSV), dynamically linked, interpreter /lib/ld-uClibc.so.0, not stripped

    

