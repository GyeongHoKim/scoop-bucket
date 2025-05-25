# Gyeongho's Scoop Bucket

[![Tests](https://github.com/GyeongHoKim/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/GyeongHoKim/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/GyeongHoKim/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/GyeongHoKim/scoop-bucket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## Available Packages

### gyeongho-custom-scripts
A collection of custom PowerShell scripts that provide Unix-like commands on Windows.

**Features:**
- `rm` - Unix-style file/folder deletion command
- `touch` - Create empty files or update timestamps
- `grep` - Search text patterns in files
- `ln` - Create symbolic links
- `du` - Disk usage statistics
- `tail` - Display the end of files
- `head` - Display the beginning of files
- `which` - Locate commands

## Installation

### Add this bucket

```pwsh
scoop bucket add gyeongho https://github.com/GyeongHoKim/scoop-bucket
```

### Install packages

```pwsh
# Install gyeongho-custom-scripts
scoop install gyeongho-custom-scripts
```

## Updating

### Update package

```pwsh
scoop update gyeongho-custom-scripts
```

### Update bucket

```pwsh
scoop update
```

## Contributing

To contribute new manifests or update existing ones:

1. Fork this repository
2. Create a new branch: `git checkout -b feature/new-manifest`
3. Add or modify manifest files in the `bucket/` directory
4. Test your changes locally
5. Commit your changes: `git commit -am 'Add new manifest'`
6. Push to the branch: `git push origin feature/new-manifest`
7. Submit a Pull Request

Please ensure all manifests follow the [Scoop App Manifest Guidelines](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests).

## License

This bucket is licensed under the MIT License.

## Author

Gyeongho Kim
