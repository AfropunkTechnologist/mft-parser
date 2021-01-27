# MFT Parser

MFT parser written in Rust to parse hard drive for MFT data.

### Overview 

mft-parser 1.0.0
Parse $MFT.

USAGE:
    mft-parser.exe [FLAGS] [OPTIONS] --source <FILE>

FLAGS:
    -b, --bool_expr    JMES Query as bool only. (Prints whole record if true.)
    -h, --help         Prints help information
    -V, --version      Prints version information

OPTIONS:
    -q, --query <QUERY>    JMES Query
    -s, --source <FILE>    The source path. Can be a file or a directory.
