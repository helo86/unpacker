# unpacker
unpacker for linux

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
