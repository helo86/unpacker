# unpacker
unpacker for linux

# Prerequisites
sudo apt install unrar p7zip-full zstd rpm2cpio cpio

# Installation
sudo cp unpack /usr/local/bin/
sudo chmod +x /usr/local/bin/unpack

# Basic extraction
./unpack archive.tar.gz

# Extract to specific directory
./unpack archive.zip /tmp/output

# Verbose mode
./unpack -v file.7z

# Keep the archive after extraction
./unpack --keep backup.tar.xz

# Force overwrite existing files
./unpack -f data.zip
